# Análise de Salários em Data Science

## 📌 Visão Geral do Projeto
Este projeto analisa salários na área de Data Science usando um dataset do Kaggle. O foco é identificar padrões salariais por cargo, país, experiência e porte de empresa.

**Dataset utilizado**: [Data Science Job Salaries (Kaggle)](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)

---

## 🔍 Principais Análises Realizadas

### 1. Exploração dos Dados
- Frequência e distribuição das categorias (cargo, país, nível de experiência)
- Estatísticas descritivas dos salários em USD
- Comparações entre países e níveis de experiência

### 2. Correlações e Tendências
| Variáveis                | Correlação |
|--------------------------|------------|
| Salário vs Experiência   | 0.42       |
| Salário vs Ano Trabalhado| 0.26       |

### 3. Top 10 Países com Maiores Salários
| País                          | Salário Médio (USD) |
|-------------------------------|---------------------|
| Malaysia                      | 200,000             |
| Puerto Rico                   | 166,000             |
| United States of America      | 149,237             |
| Canada                        | 132,223             |
| China                         | 125,404             |

---

## 📊 Principais Resultados
✅ **Cargos mais bem remunerados**:
- **Data Scientist** e **Data Engineer** lideram com salários significativamente mais altos

📈 **Experiência predominante**:
- Nível **Sênior** é o mais frequente (média de 6 anos de experiência)

🏢 **Porte das empresas**:
- Empresas de **porte médio** oferecem os salários mais altos

🌎 **Faixa salarial anual**:
- Os **top 10 países** pagam em média entre **US$ 100.000 e US$ 200.000**

---

## 🛠 Como Executar o Projeto

### 1. Instalação
```bash
pip install pandas matplotlib seaborn
