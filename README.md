# 📊 Challenge Alura - Análise de Lojas

## 🎯 Objetivo do Projeto
Este projeto faz parte do Challenge de Data Science da Alura, onde realizamos uma análise detalhada de 4 lojas para determinar qual delas deve ser vendida, baseando-nos em métricas de desempenho financeiro e operacional.

## 🔍 Análise Realizada

### Dados Analisados
- 4 Lojas com dados de vendas completos  
- Métricas incluem: faturamento, avaliações, frete médio e produtos mais vendidos  

### Principais Descobertas

#### 1. Faturamento Total por Loja
- Loja 1: R$ 1.616.347  
- Loja 2: R$ 1.567.773  
- Loja 3: R$ 1.542.048  
- Loja 4: R$ 1.458.253 ⚠️ **(MENOR FATURAMENTO)**  

#### 2. Média de Avaliações
- Loja 1: 3.98  
- Loja 2: 4.04  
- Loja 3: 4.05 ⭐ **(MELHOR AVALIAÇÃO)**  
- Loja 4: 4.00  

#### 3. Frete Médio
- Loja 1: R$ 34.69 **(MAIS CARO)**  
- Loja 2: R$ 33.62  
- Loja 3: R$ 33.07  
- Loja 4: R$ 31.28 **(MAIS BARATO)**  

#### 4. Produtos
- Mais vendido geral: **TV Led UHD 4K** (R$ 607.367,22)  
- Menos vendido geral: **Cubo mágico 8x8** (R$ 3.922,00)  

## 💡 Recomendação Final
**Loja 4 deve ser vendida ❌**

### Justificativas:
- ✅ Menor faturamento entre todas as lojas (R$ 1.458.253)  
- ✅ Diferença significativa de ~R$ 158.000 para a Loja 1  
- ✅ Apesar do frete mais baixo, não compensa o baixo faturamento  
- ✅ Avaliações medianas (4.00) não justificam manter a operação  

### Por que não as outras?
- **Loja 1:** Maior faturamento, compensa manter apesar do frete alto  
- **Loja 2:** Segundo melhor faturamento  
- **Loja 3:** Melhor avaliação dos clientes + bom faturamento  

## 📊 Visualizações
Nesta seção são apresentados **3 gráficos** utilizados para apoiar a análise e a tomada de decisão:

- Gráfico do **faturamento total por loja**
- ![Diagrama](download.png)
- Gráfico da **média de avaliações por loja**
- Gráfico do **frete médio por loja**

## 🛠️ Tecnologias Utilizadas
- Python 3  
- Pandas – Manipulação de dados  
- Matplotlib – Visualizações  
- Seaborn – Gráficos estatísticos  
- Google Colab – Ambiente de desenvolvimento  

## 📁 Estrutura do Projeto
```text
challenge-alura/
│
├── notebook/
│   └── Untitled0.ipynb          # Análise completa
│
├── data/
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
│
└── README.md
