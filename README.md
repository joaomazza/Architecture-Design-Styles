# Arquitetura da Escolha 6ASOR 

 - Leonardo Carneiro Pinho

## Equipe

- Eduardo Zanghi - 358095
- Eryckson Magno - 358550
- Fernado Tonetto - 359888
- Frederico Boaventura - 358528
- João Mazza - 357743

# Projeto de Modernização da Arquitetura de Mensageria Corporativa

## Storytelling: A Jornada da Transformação Digital na Comunicação

Em um cenário de negócios cada vez mais dinâmico e competitivo, a agilidade e a eficiência da comunicação tornaram-se pilares fundamentais para o sucesso de qualquer organização. No coração de nossas operações, o servidor de e-mail Exchange, por anos, foi o motor que impulsionou nossas interações, tanto internas quanto externas. Contudo, como toda tecnologia, ele atingiu um ponto de inflexão. A obsolescência se aproxima, e com ela, o fim do suporte, trazendo consigo riscos de segurança e uma proposta de renovação de subscrição com custos proibitivos.

Este não é apenas um desafio técnico, mas uma oportunidade estratégica de repensar e modernizar a forma como nos comunicamos. A necessidade de enviar e-mails em massa por aplicações legadas, que operam em ambientes fabris e não suportam autenticação moderna, representa um elo crítico em nossa cadeia de produção, fornecendo dados vitais para suporte e alertas imediatos. Ao mesmo tempo, nossos serviços de mensageria mais modernos, que já utilizam APIs e autenticação avançada, demandam uma plataforma robusta e escalável para garantir a entrega eficiente de suas comunicações.

Diante deste cenário, surge a necessidade de uma transformação. Uma jornada que nos levará a substituir nossa infraestrutura on-premises por uma solução SaaS de ponta, como o SendGrid da Twilio. Esta mudança não se trata apenas de trocar uma tecnologia por outra, mas de adotar uma nova filosofia de comunicação: mais flexível, segura, escalável e, acima de tudo, alinhada com as necessidades de um negócio em constante evolução.

Nossa visão é construir uma arquitetura de mensageria que não apenas resolva os desafios atuais, mas que também nos prepare para o futuro. Uma arquitetura que permita a integração transparente de nossos sistemas legados, garantindo a continuidade de nossas operações críticas, ao mesmo tempo em que oferece aos nossos desenvolvedores as ferramentas mais modernas para criar experiências de comunicação inovadoras. E, fundamentalmente, uma arquitetura que nos permita ter uma visão clara e granular dos custos de comunicação, possibilitando um rateio justo e transparente entre as áreas de negócio, transformando o TI de um centro de custo em um parceiro estratégico para o crescimento da empresa.

Esta é a história de como vamos transformar um desafio em uma oportunidade, modernizando nossa arquitetura de mensageria para impulsionar a inovação, a eficiência e o crescimento de nossa empresa nos próximos anos.



## Análise Estratégica e Respostas às Perguntas-Chave

### 1. Storyteling

### 2. O que esperamos aprender com esse projeto?

Esperamos aprender a realizar uma migração de um sistema crítico de comunicação on-premises para uma plataforma SaaS, minimizando o impacto nos negócios e garantindo a continuidade dos serviços. Além disso, pretendemos aprofundar nosso conhecimento em arquiteturas de microsserviços, integração de sistemas legados com tecnologias modernas e gestão de custos de serviços em nuvem. Este projeto será uma oportunidade para desenvolvermos competências em segurança da informação em ambientes de nuvem, especialmente no que tange à autenticação e autorização de serviços.

### 3. Que perguntas precisamos que sejam respondidas?

*   Como garantir a compatibilidade das aplicações legadas que utilizam SMTP sem autenticação com a nova plataforma SaaS?
*   Qual a melhor estratégia para migrar os dados históricos de e-mails do Exchange Server para a nova solução?
*   Como implementar um sistema de rateio de custos de envio de e-mails que seja justo, transparente e de fácil gestão?
*   Quais os impactos da nova arquitetura na latência e na entregabilidade dos e-mails, especialmente para os alertas críticos das fábricas?
*   Como garantir a segurança e a privacidade dos dados em trânsito e em repouso na nova plataforma?
*   Qual o plano de contingência em caso de falhas na nova plataforma ou problemas na migração?

### 4. Quais são os nossos principais riscos?

*   **Interrupção do serviço:** A migração pode causar interrupções no envio de e-mails, afetando as operações críticas das fábricas e a comunicação com os clientes.
*   **Segurança da informação:** A exposição de dados sensíveis durante a migração ou a configuração inadequada da nova plataforma pode levar a vazamentos de informações.
*   **Custos inesperados:** A falta de um planejamento detalhado pode levar a custos de migração e operação mais altos do que o previsto.
*   **Resistência à mudança:** As equipes podem ter dificuldades para se adaptar à nova plataforma e aos novos processos, gerando atritos e perda de produtividade.



### 5. Crie um plano para aprender o que precisamos para responder a perguntas específicas.

*   **Prova de Conceito (PoC):** Realizar uma PoC com um número limitado de aplicações legadas e serviços modernos para validar a compatibilidade com a nova plataforma e testar as funcionalidades de envio de e-mail.
*   **Consultoria especializada:** Contratar consultores especializados em migração de Exchange para SaaS e em segurança da informação para nos auxiliar no planejamento e na execução do projeto.
*   **Treinamento da equipe:** Capacitar a equipe de TI e os desenvolvedores na nova plataforma, oferecendo treinamentos e workshops sobre as melhores práticas de uso e desenvolvimento.
*   **Benchmarking:** Analisar casos de sucesso de outras empresas que realizaram migrações semelhantes, aprendendo com suas experiências e evitando cometer os mesmos erros.

### 6. Crie um plano para reduzir riscos.

*   **Migração em fases:** Realizar a migração de forma gradual, começando pelos sistemas menos críticos e avançando para os mais complexos, permitindo ajustes e correções ao longo do processo.
*   **Plano de comunicação:** Manter todas as partes interessadas informadas sobre o andamento do projeto, os possíveis impactos e os planos de contingência.
*   **Testes exaustivos:** Realizar testes de carga, segurança e compatibilidade em todas as fases da migração para garantir a estabilidade e a segurança da nova plataforma.

### 7. Quem são as partes interessadas?

*   **Diretoria de TI:** Responsável pela estratégia de tecnologia da empresa e pela aprovação do projeto.
*   **Gerentes de fábrica:** Interessados na continuidade do envio de alertas e relatórios críticos para a operação.
*   **Equipes de desenvolvimento:** Responsáveis por integrar as aplicações com a nova plataforma de mensageria.
*   **Equipe de segurança da informação:** Responsável por garantir a segurança e a conformidade da nova solução.
*   **Equipe de finanças:** Interessada na redução de custos e na implementação de um sistema de rateio eficiente.
*   **Usuários finais:** Todos os colaboradores que utilizam o e-mail como ferramenta de trabalho.

### 8. O que eles esperam ganhar?

*   **Diretoria de TI:** Redução de custos, modernização da infraestrutura, aumento da segurança e da escalabilidade.
*   **Gerentes de fábrica:** Garantia da continuidade e da confiabilidade dos alertas e relatórios.
*   **Equipes de desenvolvimento:** Acesso a uma plataforma de mensageria moderna, com APIs e documentação de qualidade.
*   **Equipe de segurança da informação:** Maior controle sobre a segurança dos e-mails e a conformidade com as políticas da empresa.
*   **Equipe de finanças:** Redução dos custos de licenciamento e operação, e um sistema de rateio de custos mais justo e transparente.
*   **Usuários finais:** Uma plataforma de e-mail mais rápida, segura e confiável, com novos recursos e funcionalidades.

### 9. Quem são os usuários?

*   **Aplicações legadas:** Sistemas automatizados que enviam e-mails de alerta e relatórios a partir das fábricas.
*   **Serviços de mensageria modernos:** Aplicações que utilizam APIs para enviar e-mails em massa para clientes e parceiros.
*   **Colaboradores:** Todos os funcionários da empresa que utilizam o e-mail para comunicação interna e externa.

### 10. O que eles estão tentando realizar?

*   **Aplicações legadas:** Enviar e-mails de forma confiável e segura, sem a necessidade de alterações em seu código-fonte.
*   **Serviços de mensageria modernos:** Enviar e-mails em massa de forma rápida e escalável.
*   **Colaboradores:** Comunicar-se de forma eficiente e segura, tanto com colegas de trabalho quanto com clientes e parceiros.

### 11. Qual o pior que pode acontecer?

O pior cenário seria uma falha total na migração, resultando na interrupção completa do serviço de e-mail por um período prolongado. Isso causaria um grande impacto nas operações da empresa, com perdas financeiras, danos à imagem da marca e insatisfação dos clientes e colaboradores. Além disso, um vazamento de dados durante a migração poderia levar a sanções legais e a perda de confiança dos clientes.



### 12. Desenhe uma arquitetura (Modelo Freeform - Versão inicial);

![Modelo Freeform](https://github.com/joaomazza/Architecture-Design-Styles/blob/main/images/freeform.png)

A arquitetura proposta é centrada em uma solução de **Microsserviços** que atua como um ponto de entrada único para todas as solicitações de envio de e-mail. Este gateway será responsável por orquestrar a comunicação entre os diferentes tipos de clientes (aplicações legadas e serviços modernos) e a plataforma de mensageria SaaS (**SendGrid**).

*   **Aplicações Legadas (SMTP):** Para as aplicações que utilizam SMTP sem autenticação, será criado um **Adaptador SMTP**. Este componente será um serviço intermediário que receberá as requisições SMTP, as converterá para chamadas de API REST e as encaminhará para o API Gateway. O Adaptador SMTP será responsável por adicionar a autenticação necessária para a comunicação com o SendGrid.
*   **Serviços Modernos (API):** Os serviços que já utilizam APIs se comunicarão diretamente com o API do sendgrid,
*   **SendGrid (SaaS):** A plataforma SendGrid será o provedor de entrega de e-mails em massa.
*   **Serviço de Rateio de Custos:** A plataforma sendgrid permite a criação de domínios e subdomínios para identificar a área de negócio, facilitando a contabilização dos valores por área.
*   **Painel de Controle (Dashboard):** Painel web de gerenciamento fornecido pela ferramenta SAAS, com SSO e MFA habilitado.

### 13. Faça uma descrição de cada um dos componentes que você desenhou;

*   **Adaptador SMTP:** Serviço que traduz requisições SMTP de sistemas legados para chamadas de API REST, adicionando a autenticação necessária.
*   **Serviços Modernos:** Aplicações que já consomem APIs e se comunicarão diretamente com o API Gateway.
*   **SendGrid:** Plataforma SaaS de envio de e-mails, responsável pela entrega, rastreamento e analytics.
*   **Painel de Controle:** Interface web para visualização dos dados de consumo e custos por área de negócio.



### 14. Descreva requisitos que você (s) considera importante e por quê?

1.  **Compatibilidade com SMTP legado:** Essencial para garantir a continuidade das operações das fábricas sem a necessidade de alterar as aplicações existentes.
2.  **Alta Disponibilidade:** A plataforma de mensageria é crítica para o negócio, portanto, deve ser altamente disponível para evitar interrupções no serviço.
3.  **Segurança:** A solução deve garantir a segurança dos dados em trânsito e em repouso, utilizando criptografia e mecanismos de autenticação robustos.
4.  **Escalabilidade:** A plataforma deve ser capaz de escalar para suportar o crescimento do volume de e-mails enviados pela empresa.
5.  **Monitoramento e Logging:** É fundamental ter um sistema de monitoramento e logging para identificar e solucionar problemas rapidamente, além de fornecer dados para o rateio de custos.

### 15. Sobre o que o diagrama ajuda você a raciocinar/pensar?

O diagrama ajuda a visualizar a interação entre os diferentes componentes da arquitetura, a identificar os pontos de integração e a entender o fluxo de comunicação. Ele nos permite raciocinar sobre a complexidade do sistema, os possíveis gargalos e os pontos de falha.

### 16. Quais são os padrões essenciais no diagrama?

*   **Adapter:** Converte a interface de um componente em outra interface que os clientes esperam.
*   **Cloud-Native:** A solução é baseada em serviços de nuvem (SaaS e PaaS), aproveitando a escalabilidade e a resiliência da nuvem.

### 17. Existem padrões ocultos?

Aparentemente, não há padrões ocultos. A arquitetura é baseada em padrões bem conhecidos e estabelecidos no mercado.

### 18. Qual é o Metamodelo?

O metamodelo utilizado é o C4 Model, que descreve a arquitetura em diferentes níveis de abstração (Contexto, Container, Componente e Código).

### 19. Pode ser discernido no diagrama único?

O diagrama freeform inicial fornece uma visão geral da arquitetura, mas não detalha todos os aspectos. Os diagramas C4 Model, que serão criados na próxima fase, fornecerão uma visão mais completa e detalhada.

### 20. O diagrama está completo?

Não, o diagrama freeform é uma versão inicial e simplificada. Ele será detalhado e refinado nos diagramas C4 Model.

### 21. Poderia ser simplificado e ainda assim ser eficaz?

O diagrama atual já é bastante simplificado. Uma simplificação maior poderia omitir detalhes importantes e prejudicar o entendimento da arquitetura.

### 22. Houve alguma discussão importante que vocês tiveram como equipe?

A principal discussão foi sobre a melhor forma de lidar com as aplicações legadas. A decisão de criar um Adaptador SMTP foi tomada após avaliar outras opções, como a alteração das aplicações legadas, que foi considerada inviável devido ao risco e ao custo.

### 23. Que decisões sua equipe teve dificuldade para tomar?

A escolha do provedor de SaaS foi uma decisão difícil. Analisamos diferentes opções, como SendGrid, Zenvia, Amazon SES e Mailgun, e a decisão foi baseada em uma combinação de fatores, como custo, funcionalidades, facilidade de integração e suporte.

### 24. Que decisões foram tomadas sob incerteza?

A estimativa do volume de e-mails enviados pelas aplicações legadas foi feita com base em dados históricos, mas há uma incerteza sobre o comportamento futuro. A arquitetura foi projetada para ser escalável e lidar com variações no volume de e-mails.

### 25. Houve algum ponto de decisão sem retorno que o forçou a desistir de uma determinada escolha?

Até o momento, não houve pontos de decisão sem retorno. A arquitetura foi projetada para ser flexível e permitir a substituição de componentes, se necessário.

### 26. Desenhe 3 Arquiteturas com o projeto em cada uma das camadas do C4 Model e gere;

Esta seção será desenvolvida na Fase 3 do projeto, com a criação dos diagramas de Contexto, Container e Componente.

## Diagramas Arquiteturais C4 Model

### 27. Diagrama de Contexto (Nível 1)

![Diagrama de Contexto](https://github.com/joaomazza/Architecture-Design-Styles/blob/main/images/diagrama_contexto.webp)

O diagrama de contexto apresenta uma visão de alto nível da arquitetura de mensageria corporativa, mostrando as interações entre os principais atores e sistemas. No centro está a Plataforma de Mensageria Corporativa, que interage com:

1.  **Aplicações Legadas de Fábrica:** Sistemas antigos que enviam e-mails usando o protocolo SMTP sem autenticação.
2.  **Serviços API Modernos:** Aplicações mais recentes que utilizam APIs para envio de mensagens.
3.  **Usuários de Negócio:** Pessoas que recebem notificações e utilizam o sistema.
4.  **SendGrid SaaS:** Plataforma externa responsável pela entrega efetiva dos e-mails.

Este diagrama ilustra claramente o papel central da nova plataforma como intermediária entre os sistemas internos e o serviço SaaS externo, destacando a necessidade de compatibilidade com diferentes protocolos e interfaces.

### Diagrama de Container (Nível 2)

![Diagrama de Container](https://github.com/joaomazza/Architecture-Design-Styles/blob/main/images/diagrama_container.webp)

O diagrama de container detalha os principais componentes da Plataforma de Mensageria Corporativa:

1.  **Microserviço Envia e-mail:** Componente central que gerencia todas as requisições de envio de e-mail.
2.  **Adaptador SMTP:** Interface que permite a comunicação das aplicações legadas com o sistema moderno.
3.  **Painel de Controle:** Interface web para visualização dos dados de consumo e custos.

O diagrama também mostra as tecnologias de comunicação utilizadas entre os componentes, como REST API, SMTP, destacando a integração com o SendGrid através de APIs.

### Diagrama de Componente (Nível 3)

![Diagrama de Componente](https://github.com/joaomazza/Architecture-Design-Styles/blob/main/images/diagrama_componente.webp)

O diagrama de componente foca no Microserviço, detalhando sua estrutura interna:

1.  **Controlador de Autenticação:** Responsável por validar as credenciais e tokens de acesso.
2.  **Controlador de Rate Limiting:** Gerencia limites de uso para evitar abusos e garantir a qualidade do serviço.
3.  **Cliente SendGrid:** Componente que se comunica diretamente com a API do SendGrid.


Este nível de detalhe permite entender como o Microserviço processa as requisições, aplica políticas de segurança e se comunica com os demais componentes do sistema.

### Link Vídeo Apresentação 

[![](https://fiapcom-my.sharepoint.com/:v:/g/personal/rm359888_fiap_com_br/ETDVv8P9J31IjOIpn-Nu6y0B2L8d72xFWhU5xogp5fbWsQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=UpoFJm)](https://fiapcom-my.sharepoint.com/:v:/g/personal/rm359888_fiap_com_br/ETDVv8P9J31IjOIpn-Nu6y0B2L8d72xFWhU5xogp5fbWsQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=UpoFJm)
