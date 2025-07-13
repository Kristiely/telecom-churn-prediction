# 📊 Desafio Telecom X – Parte 2: Prevendo Churn

Este projeto faz parte do curso de Data Science da Alura e tem como objetivo prever a evasão de clientes (churn) da operadora fictícia Telecom X, utilizando técnicas de Machine Learning e análise de dados.

---

## 🎯 Objetivo

Desenvolver modelos preditivos capazes de antecipar quais clientes têm maior probabilidade de cancelar seus serviços, permitindo à empresa tomar ações preventivas.

---

## 📁 Estrutura do Projeto

O projeto foi dividido em etapas organizadas no notebook, seguindo boas práticas de ciência de dados:

1. **Introdução**
2. **Carregamento dos Dados**
3. **Limpeza e Preparação**
4. **Codificação de Variáveis**
5. **Balanceamento com SMOTE**
6. **Normalização**
7. **Correlação e Visualizações**
8. **Divisão Treino/Teste**
9. **Modelagem (Regressão Logística e Random Forest)**
10. **Avaliação e Conclusão Estratégica**

---

## 🧪 Modelos Utilizados

- 🔹 **Regressão Logística** (modelo linear, requer normalização)
- 🔸 **Random Forest** (modelo baseado em árvore, robusto e interpretável)

---

## 📈 Principais Insights

- Clientes com **contrato mensal**, **baixo tempo de permanência** e **pagamento via débito automático** têm maior chance de evasão.
- O uso de serviços adicionais (como suporte técnico e backup online) está associado à **retenção**.
- **Random Forest** teve o melhor desempenho geral, com boa capacidade de generalização e recall.

---

## 📊 Avaliação dos Modelos

| Modelo               | Acurácia | Precisão | Recall | F1-Score |
|----------------------|----------|----------|--------|----------|
| Regressão Logística  | X%       | X%       | X%     | X%       |
| Random Forest        | X%       | X%       | X%     | X%       |

*(Substitua pelos seus resultados reais)*

---

## 💡 Recomendação Estratégica

- Oferecer vantagens para novos clientes nos primeiros meses.
- Estimular contratos de longa duração.
- Personalizar ofertas com serviços adicionais.
- Monitorar clientes com alto gasto mensal e baixo engajamento.

---

## 🧠 Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- SMOTE (balanceamento)
- Google Colab
- Git e GitHub

---

## 👩‍💻 Desenvolvido por

**Kristiely Berlitz**  
Desafio Telecom X – Parte 2  
Curso de Data Science | Alura
