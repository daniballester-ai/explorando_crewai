# 🧠 Explorando o CrewAI: Um Projeto Didático

Este projeto é um exemplo simples e prático para você entender os elementos essenciais do **CrewAI**: Agentes (Agents), Tarefas (Tasks) e Equipes (Crew). Ele foi desenvolvido para ser executado facilmente no Google Colab.

## O que é CrewAI?

CrewAI é um framework para orquestração de Large Language Models (LLMs) que permite criar equipes de agentes autônomos. Cada agente tem um papel, objetivo e histórico, e colaboram para completar tarefas complexas.

## Elementos Essenciais do CrewAI

Este projeto demonstra os três pilhos do CrewAI:

-   **Agentes (Agents):** Entidades autônomas com papéis definidos, objetivos e backstories. Neste exemplo, temos um agente "Criador de rascunhos".
-   **Tarefas (Tasks):** As ações que os agentes precisam realizar para atingir um objetivo. Definimos uma tarefa para gerar ideias de posts.
-   **Equipe (Crew):** Um grupo de agentes trabalhando juntos em um processo definido para completar uma lista de tarefas.

## Como rodar no Google Colab 🚀

Siga os passos abaixo para executar este projeto no seu Google Colab:

1.  **Abra este notebook no Google Colab:** Clone o repositório ou faça o upload do arquivo `.ipynb` para o seu Google Drive e abra-o no Colab.
2.  **Instale as bibliotecas necessárias:** Execute as células que instalam `crewai` e `langchain-google-genai`.
3.  **Configure sua API Key:** Você precisará de uma chave de API do Gemini para usar o modelo. Adicione sua chave API nos segredos do Colab (ícone de chave 🔑 no painel esquerdo) com o nome `GEMINI_API_KEY`.
4.  **Execute as células:** Prossiga executando as células do notebook em sequência. A última célula executará a equipe e imprimirá o resultado.
5.  **Verifique o arquivo de saída:** O resultado da tarefa (as ideias para posts) será salvo em um arquivo chamado `ideias_crewai.md` na mesma pasta do notebook.

## Estrutura do Projeto

O projeto consiste em um único notebook Python (`.ipynb`) que contém:

-   Instalação das bibliotecas
-   Configuração da API Key
-   Definição do Agente
-   Definição da Tarefa
-   Criação e execução da Equipe
-   Salvamento do resultado em um arquivo

## Contribuições

Sinta-se à vontade para clonar, modificar e experimentar este código para entender ainda mais sobre o CrewAI!

---

Espero que este projeto didático ajude você a dar os primeiros passos com o CrewAI! Se tiver alguma dúvida, sinta-se à vontade para abrir uma issue no GitHub. 😊
