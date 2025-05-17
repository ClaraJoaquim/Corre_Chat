# 🏃‍♀️ Corre Chat — Gere sua planilha personalizada com IA!

O **Corre Chat** é um chatbot especializado em **criar planilhas de treino de corrida personalizadas** com base nas informações fornecidas pelo usuário. A ferramenta foi construída utilizando agentes inteligentes com comunicação entre si para gerar, revisar e entregar um plano de treinos coerente, seguro e motivador.  

Este projeto foi desenvolvido como parte da **3ª Edição da Imersão IA da Alura**.

---

## 🧠 Como funciona?

O Corre Chat é composto por uma **cadeia de agentes inteligentes**, cada um com uma função específica no fluxo de criação de uma planilha de corrida personalizada:

### 👇 Agentes e suas responsabilidades:

| Agente | Função |
|-------|--------|
| **Agente 1 – Revisor de Dados** | Valida as informações fornecidas pelo usuário (ex: dias de treino, duração). Corrige dados incorretos e padroniza entradas. |
| **Agente 2 – Buscador de Treinos** | Realiza pesquisas com base nos dados do usuário para encontrar treinos eficientes e adequados ao seu perfil. |
| **Agente 3 – Planejador de Treinos** | Compara os treinos encontrados e escolhe os mais relevantes, explicando seus benefícios. |
| **Agente 4 – Treinador de Corrida** | Monta a **planilha rascunho** de 4 semanas de treino com os dados aprovados, explicando e motivando o usuário. Inclui dias de **Descanso** sempre que necessário. |
| **Agente 5 – Revisor de Planilha** | Verifica clareza, tom, correção e estrutura do plano. Aponta melhorias se necessário. |
| **Agente 6 – Finalizador de Planilha** | Aplica as correções propostas e gera a versão final da planilha de treinos. |

---

## 💡 Tecnologias utilizadas

- 🧠 **Gemini 2.0 Flash** (Google)
- 🔗 Comunicação entre agentes com `call_agent`
- 🌐 Busca de informações com `google_search`
- 🐍 Projeto em **Python**
- 📁 Estrutura modular com funções para cada agente

---

## 🛠️ Como executar

Você pode executar o projeto diretamente no **Google Colaboratory**, sem precisar instalar nada localmente.

### 📂 Passo a passo

1. Clonar o repositório:
   ```bash
   git clone https://github.com/ClaraJoaquim/Corre_Chat.git
   
2. Acessar o repositório e abrir o arquivo Corre_Chat.ipynb no Google Colab.

3. Executar as células seguindo as instruções do notebook.

---

## ✨ Sobre a Imersão IA

Este projeto foi criado como parte da **Imersão IA 3ª Edição da Alura**, com foco em desenvolver aplicações reais utilizando agentes de IA apresentados nas aulas.

---

## 💖 Por que usar o Corre Chat?

- Possui geração automática de treinos com base no seu perfil
- Linguagem motivadora e personalizada
- Fluxo de revisão por IA para garantir segurança e qualidade 

---

## 📬 Contato

Desenvolvido por **Clara Joaquim**  
🔗 [LinkedIn](https://www.linkedin.com/in/seu-perfil-aqui)
