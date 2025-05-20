![Megaline Banner](banner_Megaline.png)

# 📊 Megaline_Projeto – Análise de Planos Pré-Pagos

Este projeto analisa dados de 500 clientes da operadora Megaline ao longo de 2018 para comparar os planos pré-pagos **Surf** e **Ultimate**. O objetivo é identificar qual plano gera mais receita para a empresa e se há influência regional no comportamento dos clientes.

## 🧪 O que foi feito

- Leitura e preparação dos dados (chamadas, mensagens, internet e planos)
- Cálculo de uso mensal por cliente
- Cálculo da receita mensal por plano
- Análise exploratória com gráficos comparativos
- Testes de hipóteses estatísticas:
  - Diferença de receita entre os planos
  - Diferença de receita por região (NY-NJ vs outras cidades)

## 📌 Conclusões

- O plano **Ultimate** gera mais receita média por cliente.
- A diferença entre planos é estatisticamente significativa.
- A localização (cidade) tem influência pequena, mas significativa.
- Recomendação: Foco maior no marketing do plano **Ultimate**.

## 📁 Estrutura do Projeto

- `megaline_calls.csv` – Dados de chamadas
- `megaline_messages.csv` – Dados de mensagens
- `megaline_internet.csv` – Dados de uso de internet
- `megaline_plans.csv` – Detalhes dos planos
- `megaline_users.csv` – Informações dos usuários
- `Megaline_Analise_Planos.ipynb` – Notebook com todo o processo

## 💻 Tecnologias

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- SciPy (testes estatísticos)

---

