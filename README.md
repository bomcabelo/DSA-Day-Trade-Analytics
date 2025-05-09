# 📈 DSA Day Trade Analytics com Agentes de IA

Aplicativo interativo de análise de ações em tempo real com suporte de **Agentes de Inteligência Artificial**, desenvolvido como projeto prático de consultoria em dados para a **Data Science Academy (DSA)**. Utiliza a infraestrutura da **Groq**, **DeepSeek**, **AWS** e APIs financeiras para geração de insights automatizados e gráficos avançados.

---

## 🚀 Funcionalidades

- 📊 Análise de ações da NASDAQ com histórico de 6 meses
- 🔍 Recomendação de analistas e últimas notícias automatizadas via IA
- 🧠 Agentes de IA integrados com modelos Groq e ferramentas como DuckDuckGo e YFinance
- 📈 Gráficos interativos: preço, candlestick, médias móveis e volume
- ☁️ Deploy em Streamlit com interface amigável para uso consultivo

---

## 🧠 Tecnologias Utilizadas

- `Python 3.10+`
- [`Streamlit`](https://streamlit.io/)
- [`Plotly`](https://plotly.com/python/)
- [`yFinance`](https://pypi.org/project/yfinance/)
- [`dotenv`](https://pypi.org/project/python-dotenv/)
- [`phi`](https://github.com/phi-ai): framework para Agentes de IA
- Modelos LLM da Groq (como DeepSeek e LLaMA 3.3)
- AWS (infraestrutura de apoio ao deploy)

---

## 🧩 Instalação e Execução

1. Abra o terminal ou prompt de comando, navegue até a pasta com os arquivos e execute o comando abaixo para criar um ambiente virtual:

```bash
conda create --name dsadeployai python=3.12
```

2. Ative o ambiente

```bash
conda activate dsadeployai (ou: source activate dsadeployai)
```

3. Instale as dependências com

```bash
pip install -r requirements.txt
```

4. Crie um arquivo `.env` com suas variáveis de ambiente (se necessário para os Agentes ou APIs).

5. Execute o app com

```bash
streamlit run dsa_app.py
```

6. Digite o código (ticker) da ação desejada (ex: `MSFT`, `TSLA`, `AMZN`) e clique em **Analisar**.

---

## 📸 Interface

![interface do App](img/day-trade.png)
> Exemplo de dashboard com análises gráficas e insights gerados por IA.

```

## 🧑‍💼 Finalidade do Projeto

Este app foi desenvolvido como exemplo de uma solução prática de **Consultoria em Ciência de Dados com IA**, voltada para **Day Trade**, utilizando **modelos de linguagem de última geração (LLMs)**. Ideal para quem deseja aprender a integrar IA, finanças e visualização de dados em um único projeto.

---

## 🤝 Suporte

Dúvidas ou sugestões?  
📧 Envie um e-mail para: `rodrigues.silva.anderson@gmail.com.br`
