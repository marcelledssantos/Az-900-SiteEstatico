Desafio DIO - Site Estático na Azure

Este repositório faz parte do desafio da trilha AZ-900 e tem como objetivo mostrar a publicação de um site estático na plataforma Microsoft Azure.

Objetivo

O desafio consiste em criar uma Conta de Armazenamento, habilitar o recurso de Site Estático e disponibilizar um arquivo HTML simples acessível por meio de uma URL pública.

Passo a passo

Criação de um Grupo de Recursos

No portal da Azure, acesse "Grupos de recursos" e clique em "Criar".

Nome utilizado: rg-az900-website.

Região: East US 2

Criação da Conta de Armazenamento

No portal, acesse "Contas de armazenamento" e clique em "Criar".

Grupo de recursos: rg-az900-website.

Nome da conta: storagedesafioxxx

Desempenho: Padrão.

Redundância: LRS (Redundância local).

Habilitação do Site Estático

Dentro da conta de armazenamento criada, acesse "Site estático" no menu lateral.

Ative a opção.

Página de índice: index.html.

Upload do arquivo HTML

Acesse "Contêineres" e entre no contêiner $web.

Clique em "Carregar" e selecione o arquivo index.html.

Acesso ao site

Copie a "URL primária do ponto de extremidade" exibida em "Site estático".

Abra no navegador para visualizar o site publicado.

Estrutura do repositório
.
├── README.md
└── /imagens(Evidências)

Conclusão

A publicação do site estático na Azure demonstra de forma prática como utilizar um serviço simples da nuvem para hospedar páginas. Essa atividade ajuda a entender os conceitos básicos de grupos de recursos, contas de armazenamento e opções de redundância.

Link para o site -> https://storagedesafioxxx.z20.web.core.windows.net/ :)
