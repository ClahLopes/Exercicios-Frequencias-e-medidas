# 📊 Análise Estatística de Notas do ENEM 2023

Este repositório contém uma série de análises estatísticas sobre os dados fictícios do ENEM 2023, com foco na extração de informações relevantes para um cursinho preparatório. Os exercícios abordam conceitos como média, mediana, desvio padrão, quartis, histogramas e remoção de outliers.

## 📌 Objetivos
- Extrair informações estatísticas da base de dados do ENEM 2023.
- Identificar a disciplina com maior amplitude de nota.
- Calcular a média e a mediana das disciplinas.
- Analisar o desempenho dos 500 melhores estudantes para Ciência da Computação.
- Estudar o impacto da remoção de outliers na média nacional.
- Criar histogramas e boxplots para analisar distribuições e assimetrias.
- Determinar a melhor estratégia para substituição de valores nulos (média, moda ou mediana).

## 📊 Análises Realizadas
### 1️⃣ Identificação de Amplitude
- Determinação da disciplina com maior amplitude de nota (diferença entre maior e menor valor).

### 2️⃣ Cálculo de Média e Mediana
- Cálculo da **média** e **mediana** para cada disciplina.
- Remoção de valores nulos antes do cálculo da mediana.

### 3️⃣ Análise dos 500 Melhores Estudantes
- Aplicando pesos para cada disciplina conforme critérios da UFPE.
- Cálculo da **média ponderada** e **desvio padrão**.

### 4️⃣ Variância e Média dos Aprovados
- Análise das notas dos 40 melhores estudantes (considerando que apenas 40 vagas estavam disponíveis).
- Cálculo da variância e nova média.

### 5️⃣ Análise de Quartis e Outliers
- Cálculo do **terceiro quartil (Q3)** para Matemática e Linguagens.
- Criação de **boxplots** e identificação de outliers usando o **método IQR** (Intervalo Interquartílico).

### 6️⃣ Remoção de Outliers e Impacto na Média
- Remoção de outliers e análise de impacto na **média nacional**.
- Definição de impacto significativo como alteração > 5%.

### 7️⃣ Substituição de Valores Nulos
- Teste com **média, moda e mediana**.
- Avaliação de qual método altera menos a média geral e o desvio padrão.

## 🛠 Tecnologias Utilizadas
- **Python 3.x**
- **Pandas** para manipulação de dados
- **NumPy** para cálculos estatísticos
- **Matplotlib/Seaborn** para visualização de dados

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/[seu-usuario]/Exercicios-Frequencias-e-medidas.git
   ```



