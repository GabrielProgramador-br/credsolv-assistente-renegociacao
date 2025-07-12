# 🤖 CredSolv – Assistente Inteligente de Renegociação de Dívidas

Este projeto implementa um chatbot inteligente para renegociação de dívidas, desenvolvido com **Python**, **Streamlit** e **OpenAI (GPT-4o)**. O objetivo é automatizar o atendimento inicial de clientes inadimplentes com empatia, clareza e regras comerciais bem definidas.

---

## 🚀 Acesse o app online

👉 [https://credsolv-renegociacao.streamlit.app](https://credsolv-assistente-renegociacao.streamlit.app/)

---

## 🧠 Funcionalidades

- Apresentação humanizada do assistente virtual da CredSolv
- Regras de negociação automáticas com base no valor e tempo de atraso
- Simulação de pagamento à vista com desconto ou parcelamento com juros
- Aplicação de regras especiais para exceções, desistências e acordos rompidos
- Identificação e tratamento de mensagens agressivas com empatia
- Histórico de conversa mantido com `st.session_state`

---

## 🛠️ Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [OpenAI API (GPT-4o)](https://platform.openai.com/docs)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

---

## ▶️ Como Executar Localmente

### 1. Clone este repositório

```bash
git clone https://github.com/seu-usuario/credsolv-assistente-renegociacao.git
cd credsolv-assistente-renegociacao
```

### 2. Crie e ative um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Configure o arquivo `.env`

Crie um arquivo `.env` com base no `.env.example` e adicione sua chave da OpenAI:

```bash
cp .env.example .env
```

Edite o `.env` com sua chave:

```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

### 5. Execute o app

```bash
streamlit run app.py
```

---

## 📂 Estrutura do Projeto

```
📁 credsolv-assistente-renegociacao
├── app.py               # Código principal do chatbot
├── .env.example         # Exemplo de variáveis de ambiente
├── requirements.txt     # Dependências do projeto
├── README.md            # Documentação
```

---

## 🌐 Deploy no Streamlit Cloud

1. Suba este repositório para o GitHub
2. Acesse [streamlit.io/cloud](https://streamlit.io/cloud)
3. Crie um novo app a partir do seu repositório
4. Em "Secrets", adicione:

```toml
OPENAI_API_KEY = "sua-chave-aqui"
```

---

## 📬 Contato

**LinkedIn:** [linkedin.com/in/seu-perfil](https://linkedin.com/in/seu-perfil)  
**E-mail:** [seuemail@email.com](mailto:seuemail@email.com)
