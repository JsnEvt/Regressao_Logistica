# 🗳️ Regressão Logística Aplicada a Eleições

Projeto desenvolvido durante o curso **Formação Cientista de Dados: O Curso Completo**, ministrado por **Fernando Amaral (Udemy)**.  
O objetivo é aplicar **Regressão Logística** para prever o resultado de eleições, utilizando variáveis explicativas que influenciam o voto, como **idade, renda, escolaridade, região e indicadores sociais**.

---

## 📌 Proposta do Projeto
- Utilizar **regressão logística** para prever a probabilidade de um eleitor **votar em determinado candidato (1) ou não (0)**.  
- Analisar a relação entre variáveis socioeconômicas/demográficas e a decisão de voto.  
- Aplicar métricas de classificação para avaliar a capacidade preditiva do modelo.  
- Explorar como o modelo pode auxiliar em pesquisas eleitorais e estudos de comportamento político.  

---

## 🧠 Conceitos de Regressão Logística Abordados
- **Função Sigmoide (Logística)** → converte valores contínuos em probabilidades (0 a 1).  
- **Classificação Binária** → prever dois possíveis resultados: eleito/não eleito, votar/não votar.  
- **Odds Ratio** → interpretação do impacto de cada variável explicativa no resultado da eleição.  
- **Matriz de Confusão** → avaliação dos acertos e erros do modelo.  

---

## 📚 Bibliotecas Utilizadas
- **Pandas** → organização e tratamento do dataset eleitoral.  
- **NumPy** → cálculos matemáticos e manipulação de arrays.  
- **Scikit-learn** → implementação da regressão logística, divisão treino/teste, métricas de avaliação e geração da curva ROC.  
- **Matplotlib / Seaborn** → visualizações gráficas de dados, probabilidades e métricas do modelo.  

---

## ⚙️ Como Executar no VS Code

1. **Clone este repositório**:
```bash
git clone https://github.com/JsnEvt/Regressao_Logistica.git
cd Regressao_Logistica
```
2. Crie e ative um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
```
Ativar no Windows
```bash
venv\Scripts\activate
```
Ativar no Linux/Mac
```bash
source venv/bin/activate
```
Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Abra o projeto no VS Code clique no arquivo: Regressao logistica - Eleicao.ipynb
   Execute cada célula

📊 Resultados Esperados

Estimativa da probabilidade de vitória de um candidato com base nas variáveis analisadas.

👨‍🏫 Créditos

Projeto baseado no curso Formação Cientista de Dados: O Curso Completo de Fernando Amaral - Udemy
