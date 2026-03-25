# 📊 Análise e Previsão de Gorjetas em Restaurante

> 🚀 Projeto prático de Data Science com foco em análise exploratória e modelagem preditiva  
> 📚 Em desenvolvimento durante minha formação em Data Science pela Alura

---

## 👨‍💻 Sobre mim

Sou um estudante em transição de carreira para a área de Data Science, atualmente cursando formação em Data Science pela Alura.

Tenho como foco o desenvolvimento de habilidades práticas em:

- Análise de dados
- Python para Data Science
- Machine Learning
- Resolução de problemas de negócio com dados

Este projeto representa a aplicação prática dos meus estudos em um cenário realista.

---

## 🧠 Problema de Negócio

Como prever o valor da gorjeta de um cliente com base em características do consumo?

A capacidade de prever gorjetas pode ajudar restaurantes a:

- Melhorar a previsibilidade de receita
- Otimizar a alocação de funcionários
- Entender melhor o comportamento dos clientes

---

## 📂 Dataset

O conjunto de dados contém informações sobre o comportamento de clientes em um restaurante, incluindo:

- 💰 `total_bill` → Valor total da conta  
- 💵 `tip` → Valor da gorjeta  
- 👥 `size` → Número de pessoas na mesa  
- 📅 `day` → Dia da semana  
- 🚬 `smoker` → Indica se o cliente é fumante  

---

## 📊 Análise Exploratória de Dados (EDA)

A análise exploratória foi realizada para entender padrões e relações entre as variáveis.

### 🔍 Principais descobertas:

- A maior parte das contas está concentrada entre **10 e 20**
- Existe uma **relação positiva clara** entre valor da conta e gorjeta
- **Sábados apresentam maior faturamento total**
- **Domingos possuem maior média de gorjeta**
- Mesas com mais pessoas tendem a gerar maior consumo total

---

## 📊 Visualização

![Conta vs Gorjeta](https://raw.githubusercontent.com/Callout84/analise-gorjetas-restaurante/main/conta_vs_gorjeta.png)

📌 O gráfico evidencia uma tendência linear positiva, indicando que quanto maior o valor da conta, maior tende a ser a gorjeta.

---

## 💡 Insights de Negócio

- Clientes com contas maiores geram maior valor absoluto de gorjeta
- O percentual de gorjeta tende a diminuir conforme o valor da conta aumenta
- Finais de semana representam maior potencial de receita
- O comportamento médio de gorjeta (~15%) permite previsões confiáveis

---

## 🤖 Modelagem Preditiva (Machine Learning)

### 📌 Modelos testados:

- Regressão Linear
- Árvore de Decisão

### 📊 Resultados obtidos:

| Modelo            | MAE  | R²   |
|------------------|------|------|
| Regressão Linear | 0.76 | 0.52 |
| Árvore de Decisão| 0.84 | 0.49 |

---

## 📈 Interpretação dos Resultados

- O erro médio (~0.76) indica boa precisão para um problema real  
- O modelo explica aproximadamente **52% da variação dos dados**  
- A Regressão Linear apresentou melhor desempenho  

📌 Isso demonstra que o problema possui um padrão relativamente previsível.

---

## ▶️ Como executar o projeto

### 1. Clone o repositório
```bash
git clone https://github.com/Callout84/analise-gorjetas-restaurante.git
cd analise-gorjetas-restaurante

---













