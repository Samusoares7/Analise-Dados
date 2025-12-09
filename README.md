# 📈 Análise de Ações com Streamlit  
Aplicação interativa desenvolvida em **Python + Streamlit** para visualizar a evolução dos preços das ações do IBOV, aplicar filtros de período, comparar performance e calcular o rendimento de uma carteira simulada.

---

## 💡 Sobre o Projeto
Este projeto foi desenvolvido para praticar:

- Streamlit (componentes, sidebar, gráficos, filtros)
- Manipulação de dados com Pandas
- Coleta de dados financeiros com YFinance
- Lógica de comparação e performance de ativos
- Construção de interfaces interativas em Python

O código foi inspirado no mini-curso da **Hashtag Programação**, onde aprendi os conceitos básicos de Streamlit e depois ampliei o projeto por conta própria.

---

## ⚙️ Como funciona a aplicação

### **1. Carregamento dos tickers do IBOV**
Lê o arquivo `IBOV.csv` e formata os tickers adicionando `.SA`.

### **2. Coleta de cotações (2023–2024)**
Usa `yfinance` para baixar preços históricos diários.

### **3. Filtros interativos**
- Seleção de ações
- Seleção de período via slider

### **4. Visualização**
Gera um gráfico de linha com os preços das ações filtradas.

### **5. Performance dos ativos**
Mostra o retorno de cada ação:
- Verde para positivo  
- Vermelho para negativo  

### **6. Performance da carteira**
Simula investir **R$ 1000 em cada ativo** e calcula a performance total.

---

## 🛠️ Tecnologias Utilizadas
- Python 3.11  
- Streamlit  
- Pandas  
- YFinance  
- Datetime  

---
![Tela principal](screenshots/tela_principal.png)
![Filtros](screenshots/filtros.png)
![Gráfico de ações](screenshots/grafico_acoes.png)
![Performance](screenshots/performance.png)

## ▶️ Como rodar o projeto

### **1. Criar ambiente virtual**
```bash
python -m venv .venv

