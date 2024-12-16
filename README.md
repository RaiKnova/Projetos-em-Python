# Projetos-em-Python
Projetos realizados através do curso da Hashtag Treinamentos, ministrada pelo professor Lira. O material consiste em 4 projetos distintos, onde em cada um trabalha uma diferente área envolvendo Python, como a automação de tarefas, análise de dados, criação de planilhas, uso de IA, entre outras. 

PROJETO POWERUP O1

Automação de Formulários com PyAutoGUI

Este projeto automatiza o preenchimento de formulários em um site usando "PyAutoGUI" e dados extraídos de um arquivo 'produtos.csv' com a biblioteca Pandas. Ele realiza login automático, preenche campos como código, marca, tipo e preço, e trata dados opcionais. Também inclui rolagem de página e intervalos para garantir o funcionamento correto. É necessário ajustar as coordenadas para a tela do usuário e proteger informações sensíveis, como e-mail e senha.

PROJETO POWERUP 02 

Análise de Cancelamentos com Pandas e Plotly

Este projeto analisa dados de cancelamentos de clientes usando "Pandas" para manipulação e limpeza de dados, além de "Plotly" para criação de gráficos dinâmicos. Ele identifica padrões como atrasos elevados, contratos mensais e excesso de chamadas ao call center como principais causas de cancelamento. Após a análise, simula ajustes nas políticas da empresa para reduzir os cancelamentos, incluindo limites para atrasos e número de chamadas. O código requer ajustes conforme a base de dados utilizada.

PROJETO POWERUP 03 

Previsão de Score de Crédito com IA

Este projeto utiliza "Pandas" para manipulação de dados e "Scikit-learn" para construir modelos de IA capazes de prever o score de crédito de clientes. As etapas incluem a preparação da base de dados, transformando variáveis textuais em valores numéricos com 'LabelEncoder', divisão dos dados em treino e teste, e criação de dois modelos de IA: "Random Forest" e "KNN". Após avaliar os modelos, a Random Forest apresentou maior precisão (82% aproximado). O projeto também realiza previsões para novos clientes utilizando o modelo mais eficiente. É necessário ajustar os dados conforme a base utilizada.

PROJETO POWERUP 04

Chat Interativo com Flet

Este projeto utiliza a biblioteca "Flet" para criar um chat interativo onde os usuários podem entrar, enviar mensagens e visualizar um histórico de conversa. O fluxo do aplicativo começa com um 'popup' que solicita o nome do usuário. Após o preenchimento, o nome é usado para identificar o remetente das mensagens no chat. As mensagens são enviadas e recebidas por meio de um sistema de publicação e inscrição usando "pubsub". O chat é estruturado em uma coluna e as mensagens são organizadas em linha. O aplicativo também garante que o campo de mensagem seja limpo após cada envio e permite que os usuários vejam quem entrou no chat.


