# DIO-DESAFIO-ETL-IAGENERATIVA
Repositório para entrega dos arquivos do Desafio DIO SANTANDER (Explorando IA Generativa em um Pipeline de ETL com Python)
## Descrição da Solução
#### A solução consistiu na criação de uma planilha EXCEL contendo a classificação dos times da série A do Campeonato Brasileiro até a rodada em que o código for executado. A criação da Planilha foi necessária, devido ao impedimento de atualizar dados via API. na platoforma (UOL) usada. Foi incluído um campo adicional nessa Planilha contendo as respostas extraídas da Plataforma de IA Generativa BARD GOOGLE, com as probabilidades de cada time ser CAMPEÃO com os números de pontos ganhos obtidos até a presente rodada de consulta.

### Etapa de Extração de Dados
#### Nessa etapa utilizou-se uma API (git+https://github.com/pyanderson/python-brasileirao) que acessa todas as informações do campeonato Brasileiro (jogos, classificação etc). Os dados recuperados em formato json.

### Etapa de Transformação de Dados
#### Nessa etapa, os dados da classificação foram carregados para um DataFrame Python. 

### Etapa de Carregamento de Dados
#### Nessa etapa, foi criada uma coluna no DataFrame contendo a resposta do BART GOOGLE, sobre as probabilidades de um determinado time ser campeão até o momento do campeonato. Os dados do DataFrame foram armazenados em um planilha EXCEL.


