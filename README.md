# 📊 Análise e Previsão de Gorjetas em Restaurante

> 🚀 Projeto desenvolvido durante meus estudos em Data Science
> 📚 Nível: Iniciante (em evolução constante)

---

## 👨‍💻 Sobre mim

Sou um estudante em transição de carreira para a área de Data Science, focado em desenvolver habilidades práticas em análise de dados, Python e Machine Learning.

Este projeto faz parte da minha jornada de aprendizado aplicada, buscando resolver problemas reais com dados.

---

## 🧠 Problema de Negócio

Como prever o valor da gorjeta de um cliente com base no comportamento de consumo?

Essa previsão pode ajudar restaurantes a:

* Entender melhor o comportamento dos clientes
* Otimizar estratégias de atendimento
* Melhorar previsibilidade de receita

---

## 📂 Dataset

O dataset contém informações sobre:

* Valor da conta (`total_bill`)
* Gorjeta (`tip`)
* Número de pessoas (`size`)
* Dia da semana (`day`)
* Cliente fumante (`smoker`)

---

## 📊 Análise Exploratória (EDA)

Principais descobertas:

* A maioria das contas está entre 10 e 20
* Existe forte relação entre valor da conta e gorjeta
* Sábado possui maior faturamento total
* Domingo apresenta maior média de gorjeta
* Grupos maiores geram maior consumo

---

## 📊 Visualização

[<img src="https://raw.githubusercontent.com/Callout84/analise-gorjetas-restaurante/main/grafico.png" width="600">](https://raw.githubusercontent.com/Callout84/analise-gorjetas-restaurante/main/conta_vs_gorjeta.png)

---

## 💡 Insights de Negócio

* Clientes com contas maiores geram maior valor de gorjeta
* O percentual de gorjeta diminui conforme o valor da conta aumenta
* Finais de semana são mais lucrativos
* O comportamento médio de gorjeta gira em torno de 15%

---

## 🤖 Machine Learning

Foi desenvolvido um modelo de regressão para prever o valor da gorjeta.

### Modelos testados:

* Regressão Linear
* Árvore de Decisão

### Resultados:

| Modelo            | MAE  | R²   |
| ----------------- | ---- | ---- |
| Regressão Linear  | 0.76 | 0.52 |
| Árvore de Decisão | 0.84 | 0.49 |

### 📌 Interpretação:

* O modelo apresenta erro médio baixo (~0.76)
* Explica cerca de 52% da variabilidade dos dados
* Regressão linear foi mais eficiente que árvore de decisão

---

## ▶️ Como executar o projeto

1. Clone este repositório
2. Abra o arquivo `.ipynb` no Google Colab ou Jupyter
3. Execute as células para reproduzir a análise

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📈 Conclusão

Este projeto demonstra minha capacidade de:

* Explorar e interpretar dados
* Gerar insights de negócio
* Aplicar Machine Learning
* Comunicar resultados de forma clara

---

## 🚀 Próximos passos

* Testar modelos mais avançados
* Criar dashboard interativo
* Trabalhar com dados reais maiores

---

## 📌 Observação

Este projeto faz parte da minha evolução em Data Science.
Estou em constante aprendizado e aberto a feedbacks.

🚀 Em busca da minha primeira oportunidade na área!
