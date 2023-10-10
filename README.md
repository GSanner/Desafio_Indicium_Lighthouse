# Projeto: Desafio Indicium Lighthouse
<img src="https://www.acij.com.br/index/wp-content/uploads/2018/05/venda-carros-golpe-1024x536.jpg" />

### **Motivação:**

Testar meus conhecimentos sobre a resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos, por meio de um desafio feito pela [INDICIUM](https://indicium.tech/)

### **O desafio:**

“Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente que o core business é compra e venda de veículos usados. Essa empresa está com dificuldades na área de revenda dos automóveis usados em seu catálogo. Para resolver esse problema, a empresa comprou uma base de dados de um marketplace de compra e venda para entender melhor o mercado nacional, de forma a conseguir precificar o seu catálogo de forma mais competitiva e assim recuperar o mau desempenho neste setor. Seu objetivo é analisar os dados para responder às perguntas de negócios feitas pelo cliente e criar um modelo preditivo que precifique os carros do cliente de forma que eles fiquem o mais próximos dos valores de mercado.”

### **Objetivo:**

Sendo assim, neste relatório, vamos explorar as variáveis mais relevantes da base de dados, solucionar as questões de negócio propostas pelo desafio, formular e testar três hipóteses de negócio adicionais, além de explicar e criar um modelo preditivo capaz de precificar os carros do cliente de forma que eles fiquem o mais próximos dos valores de mercado.

-----------------------

### **Dados:**

Os dados foram fornecidos pela Indicium, e estão disponíveis para download [aqui](https://github.com/GSanner/Desafio_Indicium_Lighthouse/blob/master/Data/df_cars_train.csv) no repositório.

-----------------------
## Notebooks
Nesse repositório você encontrará dois notebooks, um deles destinado a **Análise Exploratória dos Dados**, e outro destinado ao **Machine Learning**.

[**EDA_Desafio_Lighthouse**](https://github.com/GSanner/Desafio_Indicium_Lighthouse/blob/master/Notebooks/EDA_Desafio_Lighthouse.ipynb): nesse notebook você encontrará análise exploratória dos dados, assim como a solução das questões de negócio propostas pelo desafio; a formulação e teste de três hipóteses de negócio adicionais.

#### Questões de Negócio:
**Pergunta 1:** Qual o melhor estado cadastrado na base de dados para se vender um carro de marca popular e por quê?

**Pergunta 2:** Qual o melhor estado para se comprar uma picape com transmissão automática e por quê?

**Pergunta 3:** Qual o melhor estado para se comprar carros que ainda estejam dentro da garantia de fábrica e por quê?

#### Hipóteses:
**Hipótese 1:** O hodômetro é um fato que afeta o valor de um carro usado. Ou seja, quanto mais 'rodado', menos o carro vale.

**Hipótese 2:** O fato de um veículo ser de um único dono afeta o valor dos carros usados.

**Hipótese 3:** As cor de um carro é relevante para o seu valor de mercado

[**MACHINE_LEARNING_Desafio_Lighthouse**](https://github.com/GSanner/Desafio_Indicium_Lighthouse/blob/master/Notebooks/MACHINE_LEARNING_Desafio_Lighthouse.ipynb): Neste notebook, você encontrará todo o processo de pré-processamento, modelagem de dados e a seleção do melhor modelo para o treinamento de nossos modelos preditivos. Além disso, realizaremos uma previsão na base de teste para avaliar o desempenho e determinar o quão eficaz nosso modelo se tornou.

------------

## Requisitos e Replicações:

Neste projeto, foi utilizada a versão 3.9.13 do Python

A versão do pip utilizada é a 22.2.2

A versão do git utilizada é a 2.41.0

Demais requisitos se encontram no arquivo requirements.txt

<details>
  <summary>Para utilizar este projeto, siga as instruções abaixo:</summary>

  <details>
    <summary>Passo 1: Clonar o repositório</summary>

    git clone https://github.com/GSanner/Desafio_Indicium_Lighthouse.git

  </details>

  <details>
    <summary>Passo 2: Instalar os pacotes nas versões utilizadas</summary>

    pip install -r requirements.txt
    
  </details>

</details>


