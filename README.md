## TechChallenge fase 1 | Exportação de Vinhos de Mesa do Brasil

Este notebook é minha contribuição para a Fase 1 do POSTECH - Data Analytic da FIAP, onde a proposta consiste em um deepdive de um cenário de negócios real. Aqui aplico técnicas de análise de dados para resolver um problema prático. 


### Cenário:

Assumir o papel de **Expert em Data Analytics** em uma empresa que exporta vinhos do Brasil para o mundo todo em um área recém criada pela empresa.
Aqui serei responsável pelos relatórios iniciais a serem apresentados em uma reunião de investidores e acionistas, e devo explicar a quantidade de vinhos exportados, juntamente com os fatores externos que podem vir a surgir e que interferem nas análises, tais como:

- Dados climáticos
- Dados demográficos
- Dados econômicos
- Dados de avaliações de vinhos

Para isso, o Head de Dados solicitou a construção de uma tabela contendo as seguintes informaçoes: 

- País de origem (Brasil)
- País de destino
- Quantidade em litros de vinho exportado (utilize: 1KG =1L)
- Valor em US$

A fonte de dados fornecida é ["Embrapa Uva e Vinho"](http://vitibrasil.cnpuv.embrapa.br/index.php?opcao=opt_01)

### Objetivo: 

Dizer o montante de venda de exportação nos últimos 15 anos, separando a análise por país e trazendo quais as prospecções futuras e 
possíveis ações para uma melhoria nas exportações. 

### Pergunta Norteadora definida:

"Como o Brasil pode se destacar como um player estratégico no mercado internacional de vinhos?"

## Tecnologias Utilizadas

- Python 3.12.3
- Pandas
- Matplotlib & Plotly
- NumPy
- Jupyter Notebook

## Principais Entregas

- Consolidação e limpeza de dados de exportação (2009–2024).
- Criação de visualizações interativas e comparativas.
- Análise dos países que mais consomem vinhos brasileiros.
- Avaliação do valor médio por litro exportado.
- Diagnóstico de desempenho e hipóteses para otimização.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/cbdefavori/Tech_Challenge_Fase1_AnaliseVinhos.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook `TechChallenge_Fase1.ipynb` em ambiente Jupyter ou VSCode.

## Autoria

Desenvolvido por **[Caroline Brito Defavori]**, como parte da pós-graduação em Data Analytics da [FIAP](https://postech.fiap.com.br/curso/data-analytics).
