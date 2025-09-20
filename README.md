# ChatBot com IA - Streamlit + OpenAI

Este projeto implementa um chatbot interativo utilizando **Streamlit** para frontend e backend, integrado com a API da OpenAI. O usuário envia mensagens pelo chat e recebe respostas geradas por um modelo de IA (GPT-4o).

---

## Objetivo

- Criar uma interface de chat simples e interativa.  
- Permitir conversas contínuas, mantendo o histórico das mensagens.  
- Integrar com um modelo de linguagem da OpenAI para respostas inteligentes.

---

## Funcionalidades

- Exibição do histórico de mensagens entre usuário e IA.  
- Input de mensagem pelo usuário com `st.chat_input`.  
- Resposta automática da IA exibida na interface do Streamlit.  
- Memória de sessão (`st.session_state`) para armazenar o histórico do chat.  

---

## Ferramentas Utilizadas

- **Python** – linguagem principal  
- **Streamlit** – interface web interativa  
- **OpenAI Python SDK** – integração com o modelo GPT  
- **GPT-4o** – modelo utilizado para gerar respostas

---

## Como Rodar

1. Instale as dependências:  
   ```bash
   pip install streamlit openai
Salve sua chave da OpenAI no código ou como variável de ambiente.

Execute o Streamlit:

bash
Copiar código
streamlit run nome_do_arquivo.py
Acesse o chat no navegador, envie mensagens e interaja com a IA.

Estrutura do Repositório
bash
Copiar código
chatbot-ia/
│
├── app.py                  # Código principal do Streamlit
├── README.md               # Este arquivo
└── requirements.txt        # Dependências do projeto
Autor
Pedro H. Mendonça
https://www.linkedin.com/in/pedrohmmwing/
