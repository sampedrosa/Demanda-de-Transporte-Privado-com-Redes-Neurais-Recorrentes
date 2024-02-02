# Demanda-de-Transporte-Privado-com-Redes-Neurais-Recorrentes
* **Aplicação da Rede Neural LSTM para Previsão da Demanda de Transporte Privado em uma Localização**
* **Samuel Pedrosa**


O projeto tem como objetivo demonstrar a metodologia e eficiência do Long Short-Term Memory (LSTM) para previsão de séries temporais com conhecimentos de Data Science e Neural Network.
A base selecionada foi a de registros de corridas de táxis na cidade de Nova York disponibilizada pela NYC Open Data. Dessa maneira, é possível criar e treinar um modelo para conseguir prever a demanda de táxi em uma determinada localização e tempo com a entrada sendo esses registros anteriores. Este repositório contêm o Notebook, a Apresentação e alguns dados relevantes.

**Etapas:**
1. Obter a Base de Dados.
2. Analisar, Limpar e Formatar os dados.
3. Tranformar o dataset em uma Série-Temporal.
4. Separação das Entradas e Saídas da Rede Neural.
5. Criar a arquitetura do LSTM (Keras) e gerar o modelo.
6. Aplicação e Validação dos resultados.

[Google Colab](https://colab.research.google.com/drive/1SfTmAzBA7-ERU6ajIEwLxX1YUEXjkm5i?usp=sharing)
[Google Slides](https://docs.google.com/presentation/d/1P2fXxo8Cn_1mos1xgt0yeFHbIWdPjL6iMNZstsBXPlU/edit?usp=sharing)

**Referências:**
* [Time-series Extreme Event Forecasting with Neural Networks at Uber](https://www.cs.columbia.edu/~lierranli/publications/TSW2017_paper.pdf)
* [Map of New York City (GeoJSON)](https://data.cityofnewyork.us/Transportation/NYC-Taxi-Zones/d3c5-ddgc)
* [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
* [NYC Open Data](https://opendata.cityofnewyork.us/)
