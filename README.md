# Biopython BR

[![biopython_logo_pt_br](https://user-images.githubusercontent.com/91161693/139502145-483d0c55-85b9-40c1-b133-cd4e45b196a4.png)](https://biopython.org/)
##

O Biopython Project é uma associação internacinal de desenvolvedores Python para a criação de ferramentas de biologia molecular computacional.

O site do Biopython (https://biopython.org) fornece pesquisa online para os módulos, scripts e links para desenvolveores Python que procuram ferramentas de bioinformática. Basicamente, o objetivo do Biopython é tornar mais fácil que desenvolvedores Python possam criar softwares, módulos e scripts para a bioinformática. Os recursos presentes no Biopython incluem analisadores para diversos formatos de arquivos usados na Bioinformática (FASTA, FASTQ, BLAST, ClustaW, GenBank...), acesso a serviços online (Expasy, NCBI...), interface para programas conhecidos e não tão conhecidos (ClustalW, MSMS, DSSP...), uma classe de sequência padrão, vários módulos de clusterização, uma estrutura de dados em árvores KD e até mesmo documentação.

### Instalando o Biopython
##
O Biopython pode ser instalado diretamente pelo terminal do sistema operacional com o comando **pip**:

    pip install biopython
    pip install --upgrade biopython
    pip uninstall bioython

### Requerimentos Python
##
Biopython possui foi testato e possui suporte para as seguintes versões do Python:
- Python 3.7, 3.8 e 3.9 (saiba mais em: http://www.python.org)
-  PyPy3.7 v7.3.5 ou superior (saiba mais em http://www.pypy.org)

### Dependências Opcionais
##
O Biopython requer que a biblioteca NumPy esteja instalada (siaba mais em: http://www.numpy.org), por conta disso ela é instalada automaticamente com o Biopython quando usado comando **pip**.

Algumas dependências são opcionais para usar com o Biopython que poderão ser instaladas posteriormente se necessário:

- **ReportLab** (https://www.reportlab.com/): Essa biblioteca é usada somente em `Bio.Graphics`, por conta disso ela pode ser instalada posteriormente.
