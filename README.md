# engineer-test

O Serviço de Rastreamento de Entregadores é uma aplicação que permite rastrear a localização e o histórico de posicionamento de entregadores em tempo real. A arquitetura deve ser projetada para ser escalável, eficiente e de alto desempenho.

## APIs necessárias
**Salvar Posição do Entregador:** Esta API deve permitir ao entregador enviar sua posição atual para o sistema.

**Recuperar Posição Atual do Entregador:** Esta API deve retornar a posição atual com base no ID do entregador.

**Recuperar Histórico das Últimas Posições do Entregador:** Esta API deve recuperar o histórico das últimas posições do entregador com base no ID do entregador.

**Retornar Entregadores Próximos de um Determinado Local:** Esta API retorna uma lista de entregadores que estão dentro do raio especificado da localização fornecida.

## Tecnologias Utilizadas
Você tem a liberdade de escolher as tecnologias que considerar mais apropriadas para a implementação das APIs, mas deve justificar suas escolhas.

Certifique-se de documentar seu código de forma clara e fornecer instruções para executar e testar as APIs.

Você pode utilizar bibliotecas e frameworks de código aberto, se necessário.

Será necessário a utilização do Docker e que o arquivo docker-compose esteja pronto para a execução de toda aplicação.

## Arquitetura e Considerações de Desempenho
A aplicação deve ser projetada para ser altamente escalável, permitindo o aumento no número de entregadores e solicitações de posicionamento.

O armazenamento das posições dos entregadores deve ser otimizado para leitura eficiente e consultas geoespaciais.

Implemente uma camada de cache para reduzir a carga no banco de dados em operações de leitura frequentes.

É necessário gerar eventos das alterações de posição.

Utilize uma arquitetura de microsserviços se necessário, separando as funcionalidades em serviços independentes para melhor escalabilidade e manutenção.

## Entrega do Projeto
O projeto deve ser entregue em um repositório público do GitHub e o link enviado por email para o recrutador.

Boa sorte!
