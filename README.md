Agente Inteligente de Atendimento com n8n + IA
Projeto de agente conversacional criado por Lucielle Batista Pereira, utilizando a plataforma n8n com integração de modelo de linguagem (IA), memória de contexto e consulta a base de dados estruturada.
Este projeto foi desenvolvido com foco em automação de atendimento, organização de informações e criação de agentes inteligentes reutilizáveis, podendo ser aplicado em cenários reais de suporte técnico, atendimento ao cliente e sistemas de consulta.

📌 Objetivo do Projeto

Criar um agente inteligente capaz de:
Receber mensagens de usuários em tempo real
Manter contexto da conversa (memória)
Consultar dados estruturados em tabela (Data Table)
Responder de forma automática e contextualizada
Servir como base para sistemas de atendimento automatizado

🧠 Tecnologias Utilizadas

n8n – Plataforma de automação e orquestração de workflows
LangChain (nodes do n8n) – Estrutura de agente inteligente
Google Gemini (LLM) – Modelo de linguagem utilizado para gerar respostas
Memory Buffer – Memória de curto prazo para manter o contexto da conversa
Data Table Tool (n8n) – Consulta a dados estruturados como ferramenta do agente

🏗️ Estrutura do Workflow

O workflow é composto pelos seguintes blocos principais:
Chat Trigger
Responsável por iniciar a conversa quando uma mensagem é recebida.

AI Agent
Núcleo do projeto, responsável por:

Interpretar mensagens

Decidir quando usar ferramentas

Gerar respostas inteligentes

Modelo de Linguagem (Google Gemini)
Utilizado como motor de raciocínio e geração de linguagem natural.

Memória (Simple Memory)
Permite que o agente lembre mensagens anteriores e mantenha coerência na conversa.

Data Table Tool
Funciona como base de dados conectada ao agente, permitindo consultas estruturadas.

📷 Exemplo do fluxo
<img width="462" height="294" alt="image" src="https://github.com/user-attachments/assets/348666d3-b2a8-4a07-a34f-428fafd764f4" />


💡 Possíveis Aplicações

Este tipo de agente pode ser facilmente adaptado para:
🤝 Atendimento automatizado ao cliente
🎧 Suporte técnico inteligente
📦 Consulta de produtos e pedidos
📋 FAQ automatizado
🧠 Assistentes internos para empresas
📊 Consulta de dados estruturados via chat

🚀 Como usar o projeto

Importar o arquivo .json do workflow no n8n
Configurar as credenciais do modelo de linguagem (ex: Google Gemini ou OpenAI)
Ajustar a Data Table conforme o tipo de dado desejado
Ativar o workflow
Testar o agente via interface de chat

👩‍💻 Sobre a autora

Lucielle Batista Pereira
Graduada em Sistemas de Informação, com experiência em:

Atendimento ao cliente
Suporte técnico e infraestrutura


Interesse em IA aplicada a processos e automação

📍 Brasil
🔗 LinkedIn: https://www.linkedin.com/in/lucielle-batista-5b966255/

📄 Licença

Projeto livre para fins de estudo e aprendizado.

