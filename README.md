# Extração de indicadores macroeconômicos

### 1. Objetivo: 
No cenário econômico atual, a precisão e a agilidade na análise de dados são essenciais para a competitividade das empresas. O projeto de automação da extração de diversos indicadores macroeconômicos, tanto nacionais quanto internacionais, além das paridades de moedas, visa otimizar processos críticos, como orçamentos, previsões de preços e operações importante da empresa.

- a) Disponibilização de Dados Atualizados: O projeto garantirá que a companhia tenha acesso contínuo a dados em tempo real, reduzindo o risco de decisões baseadas em informações desatualizadas.

- b) Aumentar a Assertividade: A automação proporcionará maior precisão na coleta e análise de dados, permitindo decisões mais fundamentadas e estratégias financeiras mais eficazes.
 
- c) Aceleração de Processos: A eliminação da coleta manual de dados reduzirá significativamente o tempo gasto em tarefas repetitivas, permitindo que os profissionais se concentrem em análises estratégicas e na criação de valor para a empresa.
    
- d) Facilidade na Análise de Paridades de Moedas: A implementação de ferramentas automatizadas garantirá que a empresa sempre trabalhe com as paridades de moedas mais atualizadas, minimizando riscos nas criações de orçamentos e melhorando a eficiência nas operações financeiras.

### 2. Ferramenta:
Python

### 3. Biblioteca para instalar:
'pandas', 'datetime', 'random', 'os', 'requests', 'io', 'selenium', 'fredapi'

### 4. Endereço dos arquivos:

- PETROBRAS\Integração de Dados - SUB ORC - Desenvolvimento - Desenvolvimento\Indices\Dados dos indicadores\Scripts

### 5. Qual o passo a passo? 
É necessário utilizar apenas o arquivo "Script_Geral", pois nele existe a conexão entre todos os outros scripts. A atualização do script geral fica em torno de 15 minutos de processamento. Após isso, é necessário apenas atualizar o fluxo "PBI_CAMBIO", "PBI_DESCRICAO_INDICES", "PBI_DESCRICAO_INDICES" e "PBI_SERIES_TEMPORAIS".

### 6. Scripts
Todos os scripts estão bem documentados e detalhados os passos a passo no próprio arquivo. No total são 9 scripts, sendo eles:
1. Script_Geral
2. BACEN
3. FRED
4. Cambio
5. IGPM
6. INCC
7. BACEN_projecao
8. FRED_projecao
9. SAP_saida

