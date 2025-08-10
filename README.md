# 📌 Descrição do Projeto
Este projeto tem como objetivo automatizar o atendimento de doadores para uma ONG de pets abandonados, utilizando múltiplos números de WhatsApp para lidar com alto volume de mensagens.
A aplicação gerencia interações automáticas, envia respostas personalizadas, cadastra doadores em um banco de dados e distribui a carga de atendimento entre diferentes linhas de contato. 


🎯 Funcionalidades
- Atendimento automático 24h via WhatsApp
- Respostas personalizadas para perguntas frequentes
- Cadastro automático de doadores no banco de dados
- Distribuição do fluxo de mensagens entre múltiplos números
- Relatórios de conversas e doações
- Integração com CRM interno da ONG

| Tecnologia / Biblioteca              | Finalidade                                                                                              |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| **Node.js**                          | Ambiente de execução do JavaScript no servidor                                                          |
| **Express.js**                       | Criação de rotas e API REST para integração com o WhatsApp e o painel administrativo                    |
| **Baileys** (ou **whatsapp-web.js**) | Comunicação direta com a API não oficial do WhatsApp Web, envio e recebimento de mensagens              |
| **MySQL** (ou MongoDB)               | Armazenamento de dados dos doadores, histórico de conversas e estatísticas                              |
| **dotenv**                           | Armazenar credenciais e variáveis sensíveis de forma segura                                             |
| **nodemon**                          | Facilitar o desenvolvimento reiniciando automaticamente o servidor a cada alteração no código           |
| **Socket.IO**                        | Comunicação em tempo real entre o servidor e o painel web para monitoramento das conversas              |
| **cors**                             | Habilitar conexões de outros domínios, garantindo segurança na API                                      |
| **axios**                            | Consumo de APIs externas, caso seja necessário integrar com gateways de pagamento ou plataformas de CRM |
| **jsonwebtoken (JWT)**               | Controle de autenticação e segurança no acesso ao painel administrativo                                 |




