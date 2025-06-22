
## 📊 Análise de Evasão de Clientes - Telecom X

Este projeto tem como objetivo analisar os dados de clientes da empresa **Telecom X** para identificar padrões de evasão (churn) e propor estratégias de retenção com base em dados reais.

---

### 📁 Estrutura do Projeto

- `telecomx_br.ipynb`: Notebook principal com todas as etapas do projeto.
- Fonte dos dados: [TelecomX_Data.json](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/main/TelecomX_Data.json)

---

### 🚀 Etapas Realizadas

#### 1. **Extração**
- Leitura de dados em formato JSON diretamente do GitHub.

#### 2. **Transformação**
- Normalização de colunas aninhadas (`customer`, `phone`, `internet`, `account`).
- Conversão de tipos de dados para análise numérica.
- Tratamento de valores ausentes.

#### 3. **Análise Exploratória**
- Visualização da distribuição de churn.
- Análise de churn por tipo de contrato e faixa etária.
- Identificação de padrões relevantes para retenção de clientes.

#### 4. **Conclusões**
- Clientes com **contratos mensais** têm maior propensão ao churn.
- **Idosos** (SeniorCitizen) também apresentam maior taxa de evasão.

---

### 📌 Principais Insights

- Contratos de curto prazo estão fortemente associados à evasão.
- Estratégias específicas podem ser aplicadas para públicos mais vulneráveis ao churn.

---

### 💡 Recomendações

- Incentivar contratos de longo prazo com benefícios exclusivos.
- Criar programas de suporte e fidelização para clientes idosos.
- Monitorar continuamente os indicadores de churn para ações preventivas.

---

### 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Seaborn & Matplotlib
- Google Colab

---

### 📄 Relatório Final

O relatório completo com gráficos e análises está disponível no notebook `telecomx_br.ipynb`.

---


