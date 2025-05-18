# 👮🧠 Agente Cidadão Inteligente - ACI ChatBot

Este projeto implementa um sistema de chatbot inteligente para fornecer informações sobre serviços sociais e outros recursos em uma determinada localização, passada pelo usuário durante a inicialização da conversa, utilizando agentes de IA e a API do Google Gemini.

##   Índice

1.  [Descrição](#descrição)
2.  [Funcionalidades](#funcionalidades)
3.  [Tecnologias Utilizadas](#tecnologias-utilizadas)
4.  [Uso](#uso)
5.  [Contribuição](#contribuição)
6.  [Licença](#licença)
7.  [Créditos e Agradecimentos](#créditos-agradecimentos)

##  💭 Descrição <a name="descrição"></a>

O projeto ACI (**Agente Cidadão Inteligente**) tem como objetivo facilitar o acesso dos cidadãos de uma determinada região, a informações sobre serviços sociais e recursos relacionados com áreas como: **Educação**, **Saúde** e **Segurança**. Ele utiliza um chatbot alimentado pela API do Google Gemini para responder a perguntas dos usuários de forma inteligente e fornecer detalhes relevantes sobre os serviços disponíveis. De forma **sucinta**, **confiável** e **amigável**, atingindo todos e qualquer público-alvo.

O sistema é projetado para:

* Entender as perguntas dos usuários em linguagem natural -- muitas das vezes **informal**.
* Buscar informações atualizadas sobre os serviços.
* Fornecer respostas **claras**, **concisas** e **úteis**.
* Citar as _fontes_ das informações fornecidas.

## ⚙️ Funcionalidades <a name="funcionalidades"></a>

* Resposta a perguntas sobre serviços sociais (saúde, assistência social, educação, segurança).
* Busca de informações utilizando a ferramenta de busca do [**Google**](https://www.google.com/).
* Fornecimento de detalhes como endereços, contatos, horários de funcionamento, documentos necessários, etc.
* Tratamento de entradas inválidas do usuário (perguntas vazias).
* Contexto da conversa para manter a continuidade do diálogo -- armazenamento de histórico para uma mesma sessão.

## 🛠️ Tecnologias Utilizadas <a name="tecnologias-utilizadas"></a>

* [Google Colab](https://colab.research.google.com/)
    * [Python 3](https://www.python.org/)
    * [Google Gemini API](https://gemini.google.com/app?hl=pt-PT)
    * [Google ADK (Agent Development Kit)](https://google.github.io/adk-docs/)
    * Bibliotecas: `os`, `google.colab.userdata`, `google.genai`, `google.adk.agents`, `google.adk.runners`, `google.adk.sessions`, `google.adk.tools`, `IPython.display`, etc.

* É necessário ter uma conta da Google, e uma chave API do [Google AI Studio](https://aistudio.google.com/prompts/new_chat). Para mais informações, procure por vídeos tutoriais de como gerar sua API Key e vincular no seu projeto do Google Colab.

* É utilizada o modelo `gemini-2.5-flash-preview-04-17-thinking`, mas em casos de falhas, pode ser alterado para o modelo estável no momento, `gemini-2.0-flash`.

## ⏯️ Uso <a name="uso"></a>

1.  Execute o script Python (`.ipynb` ou `.py`).
    * Como recomendação, use o Google Colab como ambiente de execução.
2.  O chatbot será iniciado e você poderá interagir com ele através do console - será criado um box para inserir suas mensagens.
3.  Faça perguntas sobre serviços sociais em uma determinada localização (de preferência a sua).
4.  O chatbot fornecerá as informações solicitadas.  

Exemplo: <br>

**😃 Você:** Quais os documentos necessários para o Bolsa Família?  
**👮 ACI:** Os documentos necessários são RG, CPF, comprovante de residência e certidão de nascimento das crianças. [Fonte: Site do Governo Federal]

## 🌟 Contribuição <a name="contribuição"></a>

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, por favor, abra uma issue ou envie um pull request.

Como melhorias, podemos nos atentar na **velocidade** das respostas do modelo, bem como vincular a alguns serviços do próprio _workspace Google_, facilitando as tarefas do usuário, cliente dessas plataformas.

## 📜 Licença <a name="licença"></a>

Este projeto é licenciado sob a [Licença MIT](https://github.com/CesarImperas/agente-cidadao-inteligente/blob/main/LICENSE) - 2025.

## Créditos e Agradecimentos <a name="créditos-agradecimentos"></a>

* Desenvolvido por [Caio Cesar Vieira Cavalcanti](https://www.linkedin.com/in/caiocesarvieira/)
* Projeto realizado como exercício de todo o aprendizado passado durante a [**Imersão IA Alura + Google Gemini**](https://www.alura.com.br/cursos-online-tecnologia), com a participação de ilustres e especiais mentores nesse mergulho ao "mundo da IA":
    * [**Fabrício Carraro**](https://www.linkedin.com/in/fabriciocarraro/)
    * [**Luciano Martins**](https://www.linkedin.com/in/lucianommartins/)
    * [**Valquíria Alencar**](https://www.linkedin.com/in/valquiria-alencar/)  

Gostaria de expressar minha especial gratidão à Alura por proporcionar esta valiosa oportunidade de aprofundar meus conhecimentos no fascinante universo da Inteligência Artificial.

Agradeço o aprendizado sobre tópicos importantes da IA, como:

* O que é Inteligência Artificial?
* Boas práticas de comandos de entrada para modelos de linguagem.
* A arte da Engenharia de Prompt.
* O desenvolvimento do primeiro chatbot.
* A compreensão dos Agentes da IA.

Tudo isso utilizando o [**Google Gemini**](https://gemini.google.com/app?hl=pt-PT), uma plataforma inovadora e em constante evolução no campo das LLMs.