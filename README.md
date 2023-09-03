# DIO-DESAFIO-ETL-IAGENERATIVA
Repositório para entrega dos arquivos do Desafio DIO SANTANDER (Explorando IA Generativa em um Pipeline de ETL com Python)
## Descrição da Solução
#### A solução consiste na criação de uma planilha EXCEL contendo a classificação dos times da série A do Campeonato Brasileiro até a rodada em que o código for executado. Isso por conta do impedimento de atualizar dados via API. Foi incluído um campo adicional nessa Planilha contendo as respostas extraidas da Plataforma de IA Generativa Bard GOOGLE, contendo a probabilidade de um time ser CAMPEÃO com os números de pontos ganhos obtidos até a presente rodada de consulta.

### Etapa de Extração de Dados
#### Nessa etapa utilizou-se uma API (git+https://github.com/pyanderson/python-brasileirao) que acessa todas as informações do campeonato Brasileiro (jogos, classificação etc). Os dados recuperados em formato json.

### Etapa de Transformação de Dados
#### Nessa etapa, os dados da classificação foram carregados para um DataFrame Python. 

### Etapa de Carregamento de Dados
#### Nessa etapa, foi criada uma coluna no DataFrame contendo a resposta do BART GOOGLE, sobre as probabilidades de um determinado time ser campeão até o momento do campeonato. Os dados do DataFrame foram armazenados em um planilha EXCEL.


