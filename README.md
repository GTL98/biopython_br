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
- **Matplotlib** (http://matplotlib.org/): Usada em `Bio.Phylo` para a visualização das árvores filogenéticas.
- **NetworkX** (https://networkx.org/) e **PyGraphviz** (https://pygraphviz.github.io/) ou **pydot** (https://github.com/pydot/pydot): Essas bibliotecas são usadas em funções específicas em `Bio.Phylo`.
- **RDFLib** (https://github.com/RDFLib/rdflib): Usada no analisador CDAO em `Bio.Phylo`.
- **psycopg2** (https://www.psycopg.org/) ou **PyGreSQL** (http://www.pygresql.org/): Essas bibliotecas com o `BioSQL` para acessar a base de dados PostgreSQL.
- **MySQL Conector/Python** (https://dev.mysql.com/downloads/connector/python/): Usada pelo `BioSQL` para acessar a base de dados MySQL. É suportado também pelo PyPy.
- **mysqlclient** (https://github.com/PyMySQL/mysqlclient): Esse é um fork do antigo MySQLdb e é usado pelo `BioSQL` para acessar a base de dados MySQL. É suportado também pelo PyPy.

Além das bibliotecas, existe uma série de ferramentas úteis que podem ser instaladas, como o NCBI, BLAST, EMBOSS ou ClustalW.

### Documentação
##
Se você deseja analisar a documentação de um módulo específíco, basta acessar https://biopython.org/wiki/Documentation. Caso queria algo mais detalhado, leia o documento **Biopython Tutorial and Cookbook**:
- HTML - http://biopython.org/DIST/docs/tutorial/Tutorial.html
- PDF - http://biopython.org/DIST/docs/tutorial/Tutorial.pdf

Se você quiser uma introdução rápida ao Biopython, recomendo que veja o E-book feito pelo pessoal da Universidade Federal de Minas Gerais (UFMG) do setor de Bioinformática:
- E-book: https://www.researchgate.net/publication/344756626_Introducao_a_Programacao_para_Bioinformatica_com_Biopython

### Origem da tradução
## 
Resolvi realizar a tradução do Cookbook do Biopython para deixar mais acessível a documentação, uma vez que não há uma documentação completa em português para o Biopython, além de ajudar os desenvolvedores que usam essa biblioteca.
