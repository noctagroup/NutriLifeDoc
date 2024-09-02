# <span id="topo">

<div align="center">
    
![banner](https://github.com/noctagroup/NutriLifeDoc/blob/main/imagens/1.png)

</div>
    
<p align="center">
    <a href="#sobre">Sobre</a>  |  
    <a href="#backlogs">Backlogs</a>  |  
    <a href="#tecnologias">Tecnologias</a>  |  
    <a href="#equipe">Equipe</a>
</p>    
    
<span id="sobre">
    
## 📑 Sobre o projeto

> _Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos_

<a href="">📌<strong>Documentação</strong></a>

📌Status do Projeto: **Em andamento** 🚧

### 🏁 Entregas de Sprints

Cada entrega foi realizada a partir da criação de uma branch neste repositório com um relatório completo de tudo o que foi desenvolvido naquela sprint. Observe a relação a seguir:
| Sprint | Previsão de entrega | Status | Histórico |
|:--:|:----------:|:-------------------|:-------------------------------------------------:|
| 01 | 17/09/2024 | 🚀 Iniciado | [ver relatório]() |
| 02 | 08/10/2024 | 🚧 Não iniciada | [ver relatório]() |
| 03 | 08/11/2024 | 🚧 Não iniciada | [ver relatório]() |

→ [Voltar ao topo](#topo)

<span id="backlogs">

## 🎯 Backlogs, Épicos & User Stories

### Requisitos

| ID Requisito | Tipo Requisito      | Nome                                 | Descrição                                                                                                                                                                                                                                                             |
| ------------ | ------------------- | ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF-01        | Funcional           | Registro de Usuario                  | O sistema deve permitir que novos usuários se registrem fornecendo informações como nome, e-mail e senha. O sistema deve enviar um e-mail de confirmação de registro para o usuário.                                                                                  |
| RF-02        | Funcional           | Login de Usuario                     | O sistema deve permitir que usuários registrados façam login usando e-mail e senha. O sistema deve validar as credenciais de login e, em caso de erro, exibir uma mensagem apropriada.                                                                                |
| RF-03        | Funcional           | Calcular Metabolismo Basal           | O sistema deve calcular o metabolismo basal do usuário com base nos dados fornecidos na anamnese e no objetivo nutricional selecionado. O sistema deve exibir o valor calculado das necessidades calóricas diárias do usuário.                                        |
| RF-04        | Funcional           | Registrar Refeiçoes                  | O sistema deve permitir que o usuário selecione e registre alimentos como parte de uma refeição. O sistema deve calcular e exibir o total de calorias e nutrientes da refeição registrada.                                                                            |
| RF-05        | Funcional           | Receber Dieta Balanceada             | O sistema deve gerar uma opção de dieta balanceada baseada nas necessidades calóricas e objetivos do usuário. O sistema deve permitir que o usuário veja e siga a dieta sugerida.                                                                                     |
| RF-06        | Funcional           | Variar Alimentos na Dieta            | O sistema deve oferecer opções alternativas para os alimentos da dieta sugerida. O sistema deve permitir que o usuário substitua alimentos de forma simples e rápida.                                                                                                 |
| RF-07        | Funcional           | Monitorar Progresso Nutricional      | O sistema deve exibir um histórico de progresso nutricional do usuário, mostrando as calorias consumidas, metas alcançadas e mudanças de peso. O sistema deve gerar gráficos e relatórios que ajudem o usuário a visualizar seu progresso.                            |
| RF-08        | Funcional           | Preencher Anamnese                   | O sistema deve permitir que usuários registrados façam login usando e-mail e senha. O sistema deve validar as credenciais de login e, em caso de erro, exibir uma mensagem apropriada.                                                                                |
| RFD-01       | Funcional DESEJAVEL | Registro de Dieta do Paciente        | O sistema deve permitir que nutricionistas criem dietas personalizadas e as enviem aos seus pacientes por meio do aplicativo.                                                                                                                                         |
| RFD-02       | Funcional DESEJAVEL | Comunicação com Pulseira Inteligente | O sistema deve integrar-se com dispositivos de pulseira inteligente para sincronizar automaticamente as calorias queimadas e ajustar o gasto calórico diário do usuário.                                                                                              |
| RFD-03       | Funcional DESEJAVEL | Criação de Alarmes com Dieta         | O sistema deve permitir que o usuário configure alarmes que lembram sobre os horários de alimentação conforme a dieta planejada.                                                                                                                                      |
| RFD-04       | Funcional DESEJAVEL | Visualização Interativa da Refeição  | O sistema deve permitir que o usuário interaja com os alimentos de uma refeição em tempo real, ajustando porções e visualizando os impactos nutricionais.                                                                                                             |
| RNF-01       | Não Funcional       | Desempenho                           | O sistema deve responder às ações do usuário em no máximo 2 segundos. O aplicativo deve ser capaz de lidar com até 10.000 usuários simultâneos sem degradação significativa de desempenho.                                                                            |
| RNF-02       | Não Funcional       | Usabilidade                          | O sistema deve ser intuitivo e fácil de navegar, permitindo que novos usuários compreendam como usar as principais funcionalidades em menos de 5 minutos. O sistema deve fornecer feedback claro para as ações do usuário, incluindo mensagens de erro e confirmação. |
| RNF-03       | Não Funcional       | Escalabilidade                       | O sistema deve ser escalável para acomodar o crescimento do número de usuários sem necessidade de grandes mudanças na infraestrutura. O sistema deve permitir a fácil adição de novas funcionalidades sem afetar negativamente as existentes.                         |

### Epicos

| ID Épico | Nome                                                | Descrição                                                                                                                                                                       |
| -------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP-01    | Gerenciamento de Usuários                           | Este épico abrange todas as funcionalidades relacionadas ao gerenciamento de contas de usuário, incluindo registro, login e gerenciamento de perfis.                            |
| EP-02    | Avaliação Inicial e Personalização                  | Este épico envolve a coleta de informações de saúde do usuário e a personalização dos serviços do aplicativo com base nessas informações.                                       |
| EP-03    | Planejamento e Registro de Dieta                    | Este épico cobre a criação de planos alimentares, o registro de refeições e a personalização de dietas para ajudar os usuários a atingir seus objetivos nutricionais.           |
| EP-04    | Monitoramento e Acompanhamento                      | Este épico envolve funcionalidades para monitorar e acompanhar o progresso nutricional do usuário ao longo do tempo.                                                            |
| EP-05    | Funcionalidades Avançadas e Integrações (Desejável) | Este épico inclui funcionalidades adicionais que aumentam a experiência do usuário, como integração com dispositivos externos e funcionalidades específicas para nutricionistas |

### User Stories

| ID Épico | ID US | Nome                                 | Descrição                                                                                                                                                                                                                 |
| -------- | ----- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP-01    | US-01 | Registro de Usuário                  | Como um novo usuário, eu quero me registrar no aplicativo para poder acessar todas as funcionalidades de controle nutricional.                                                                                            |
| EP-01    | US-02 | Login de Usuário                     | Como um usuário registrado, eu quero fazer login no aplicativo para acessar minhas informações e acompanhar meu progresso.                                                                                                |
| EP-02    | US-03 | Preencher Anamnese                   | Como um usuário, eu quero preencher uma anamnese inicial adaptável aos meus objetivos para que o aplicativo possa entender minhas necessidades e preferências nutricionais.                                               |
| EP-02    | US-04 | Calcular Metabolismo Basal           | Como um usuário, eu quero que o aplicativo calcule meu metabolismo basal baseado nas informações da anamnese alinhadas ao meu objetivo para saber minhas necessidades calóricas diárias.                                  |
| EP-03    | US-05 | Registrar Refeições                  | Como um usuário, eu quero ser capaz de navegar de forma fluida entre as opções de alimentos e registrá-las em conjunto como uma refeição.                                                                                 |
| EP-03    | US-06 | Receber Dieta Balanceada             | Como um usuário, eu quero receber uma opção de dieta balanceada baseada nas minhas necessidades calóricas e objetivo.                                                                                                     |
| EP-03    | US-07 | Variar Alimentos na Dieta            | Como um usuário, quero ter a opção de variar os alimentos sugeridos na dieta para manter uma alimentação diversificada e saborosa de maneira simples através de alternativas disponibilizadas por alimento no aplicativo. |
| EP-04    | US-08 | Monitorar Progresso Nutricional      | Como um usuário, eu quero monitorar meu progresso nutricional para ver como estou evoluindo em relação ao meu objetivo.                                                                                                   |
| EP-05    | US-09 | Registro de Dieta do Paciente        | Como um nutricionista, eu quero poder criar uma dieta personalizada no sistema e enviar de alguma forma ao meu paciente.                                                                                                  |
| EP-05    | US-10 | Comunicação com Pulseira Inteligente | Como um usuário, eu quero que as calorias contabilizadas pela minha pulseira inteligente sejam debitadas do meu gasto calórico diário automaticamente.                                                                    |
| EP-05    | US-11 | Criação de Alarmes com Dieta         | Como um usuário, gostaria que o aplicativo colocasse alarmes que me levassem à minha dieta nas horas estipuladas para a alimentação.                                                                                      |
| EP-05    | US-12 | Visualização Interativa da Refeição  | Como um usuário, gostaria que durante a refeição eu pudesse gerenciar os alimentos e nutrientes de forma interativa pelo aplicativo com suas funcionalidades de gerenciamento nutricional.                                |

→ [Voltar ao topo](#topo)

<span id="tecnologias">

## 🛠️ Tecnologias

As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

→ [Voltar ao topo](#topo)

<span id="equipe">

## 👥 Equipe

| Integrante                    | Função        | Github                           | LinkedIn                                                          |
| ----------------------------- | ------------- | -------------------------------- | ----------------------------------------------------------------- |
| Otavio Abreu dos Santos Silva | Product Owner | https://github.com/otavioabreu27 | https://www.linkedin.com/in/o-abreu/                              |
| Flavio Eduardo Linguanotto    | Scrum Master  | https://github.com/linguanotto   | https://www.linkedin.com/in/flavio-linguanotto-b587361a4/         |
| João Vitor Cabral Procópio    | Dev Team      | https://github.com/joaoprocopio  | https://linkedin.com/in/joao-procopio                             |
| Igor Vinicius Santos Fonseca  | Dev Team      | https://github.com/fonsecaigor   | https://www.linkedin.com/in/igor-fonseca                          |
| Rafael Estevam de Siqueira    | Dev Team      | https://github.com/rafaelres     | https://www.linkedin.com/in/rafael-estevam-de-siqueira-77891423a/ |
| Beatriz Roberto Montanini     | Dev Team      | https://github.com/BiaMontanini  | https://www.linkedin.com/in/beatriz-montanini-b69b451b9/          |

→ [Voltar ao topo](#topo)
