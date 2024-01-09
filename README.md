# Detecção de Fake News com Redes Neurais

<img align="center" alt="EN" height="30" width="30" src="https://em-content.zobj.net/thumbs/120/whatsapp/326/flag-united-states_1f1fa-1f1f8.png"> _Click [here](https://github.com/raffaloffredo/fake_news_detection) to English-EN_   
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj68VWjYaUQcC_2n_Pp2mgYwhrau97wNrhzUXCP_yJnKf95yTEl88tNOT8vC-4wMxs4xtaeflYwLIDwl8Ul5cZz2EB25nqBKrQ2MELo4LRjTiyJ7l8Li9ygM5rjmLex6xtNpXgCXIbokYqxRPsgE5m-ojz2ksDB89AHM_GyPE2mGaOdua9hp3ACagdRDYw/s16000/capa_ptbr.png">
</p>
<br/>

## Sobre o projeto
As fake news têm sido um problema recorrente na nossa Era pós globalização e com fácil acesso à internet. Para combatê-las é necessário primeiro identificá-las. Isso é possível com o uso de algoritmos treinados para essa finalidade.

Nesse estudo criei um modelo supervisionado de aprendizado de máquina com o uso de redes neurais para classificar se uma notícia é ou não confiável. Para isso foi feita uma análise exploratória do conjunto de dados, limpeza e tratamento dos dados, a padronização de textos. Foram criadas duas nuvens de palavras para se familiarizar com os termos mais utilizados nos artigos, bem como foram analisados os autores com a maior quantidade de notícias nesse conjunto de dados. Em seguida, se realizou o pré-processamento necessário para o uso do TensorFlow por meio das técnicas de tokenização e _padding_. A construção do algoritmo foi modelada de acordo com o problema, por isso, sua base é uma rede neural sequencial empilhada por camadas que conta com: _Embedding_, _Conv1D_, _GlobalMaxPool1D_ e _Dense_. Após a inserção de novos dados no modelo, avaliou-se sua performance por meio dos valores de acurácia e recall, além da construção da matriz de confusão.

* **[Projeto na íntegra](https://github.com/raffaloffredo/fake_news_detection_portuguese/blob/main/%5BLoffredoDS%5D_Detec%C3%A7%C3%A3o_de_Fake_News_com_Redes_Neurais.ipynb)**
* **[Artigo Completo](https://medium.com/@loffredo.ds/detec%C3%A7%C3%A3o-de-fake-news-com-redes-neurais-cd2ebfa4af33)**
* **[Artigo Resumido (Resultados)](https://www.linkedin.com/pulse/constru%25C3%25A7%25C3%25A3o-de-uma-solu%25C3%25A7%25C3%25A3o-para-combate-fake-news-com-loffredo-4zamf)**

<br/>

## Material Extra
Os resultados obtidos nesse estudo foram condensados na apresentação abaixo.
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjSsWoZCEKDlYs2HMT4GYT2to2Sz8sIrtAN3IBatNMayRaR_U4nEsDbI4pNo9YBLRshrR2J4jDkuvwBTZjfLERVDiuyWklV04P6Y2KVAq7iJD1kaDxrGEWFSCJCEGfLLXfVZ6ClT6cTwY2hCrGkPIB0jJ9lkIFSTmE2cJscC_KAvqWKfNz7_tFSql__5S4/w640-h360/Slide1.PNG" width="60%">
</p>
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhC1yq3rp8z23Rhb5GZQ9EZOPG4w6fcT8_2hDK9to6JcYW1USW8IwD0dd9RQqvwxGxsJeBtoc24G8ywABlJkfWGcCjJt3oq4-X_VsbIRl8Kar2HohR1OC04rmJIqsDfdqdFwPcy1koc_NMThaB24NIjhS6fKOVbW6E7g2o25ahZiZ-_cbvaSbrAryC8Xoc/w640-h360/Slide2.PNG" width="60%">
</p>
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjb6fqZlxkX0lSJeVZqXN4coQysdF2uCE7K3guwZUupmTVCNNPnph5CTxuWxXq10mxC9M3J08fSon-k-yWQNe2AVpH5GBeEaGjzay2BmPKTVwDK47Rpd0oBHI3M6Y0Rk2dZIQwCPd8JOchAXgBOTmeFhqhRggY6HZ8P1g-Nspr2kd2tn5xRlUEnrmPTZ9s/w640-h360/Slide3.PNG" width="60%">
</p>
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgKlGlYCQker2LaPGx7uzNivYZHtPyMM7JS5QoCt8ESNC09KMZdAHb4KWJ4Z7CnP5H2v2wkVlCB9w8_xh1vpLZkw6yU9_zoVncssi1KBCYpZSiKgixpNKjQtd2iZhYqJjOO2dZ1oUSjlcqUFAfczj-vP4WY284ImZaHXza5qIlfJP5LN_DN-4oJAtqcess/w640-h360/Slide4.PNG" width="60%">
</p>
<br/>

## Outros projetos

* **[Análise de Risco de Crédito](https://github.com/raffaloffredo/credit_risk_analysis_portuguese)**
* **[Análise de séries temporais para previsão de demanda](https://github.com/raffaloffredo/demand_forecasting_with_time_series_portuguese)**
* **[Classificação para identificar a saúde de um feto](https://github.com/raffaloffredo/fetus_health_classification_portuguese)**
* **[Previsão de Custo de Seguro de Vida](https://github.com/raffaloffredo/life_insurance_price_prediction_portuguese)**
* **[Previsão de Churn](https://github.com/raffaloffredo/churn_prediction_portuguese)**
* **[Detecção de fraude em cartão de crédito](https://github.com/raffaloffredo/fraud_detection_portuguese)**
* **[Airbnb New York](https://github.com/raffaloffredo/airbnb_new_york_portuguese)**
* **[Estudo atualizado sobre COVID-19 no Brasil e no mundo](https://github.com/raffaloffredo/covid_2023_portuguese)**
<br/>

 ## Contatos
<div>
  <a href="https://www.linkedin.com/in/raffaela-loffredo/?locale=en_US" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://sites.google.com/view/loffredo/" target="_blank"><img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white"></a>
  <a href="https://medium.com/@loffredo.ds" target="_blank"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"></a>
</div>
