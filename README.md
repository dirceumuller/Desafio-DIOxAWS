# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 30/01/2026
Empresa: Abstergo Industries 
Responsável: Dirceu Amilton Müller

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Dirceu Amilton Müller. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:**
- Amazon Aurora
- Banco de Dados Relacional online
- Transferir os bancos de dados da Abstergo Industries para a nuvem, como a base de clientes, de fornecedores, de produtos do catálogo e estoque disponível, além de outras bases menores necessárias para a operação. Nessa primeira etapa, a compatibilidade dos bancos de dados permite que os dados sejam migrados de forma transparente, mantendo inicialmente os sistemas originais já em uso e mudando apenas o caminho para onde os softwares legados apontam no momento de acessar/armazenar os dados. De imediato, o custo de manutenção dos servidores de espaço de armazenamento é eliminado, além do valor de licenciamento para o banco de dados ser reduzido imensamente. Ainda é possível leiloar os equipamentos que não serão mais utilizados de forma a interromper as perdas por depreciação.

**Etapa 2:**
- Amazon ECS
- Conteinerização do software legado
- Como houve a decisão de não refatorar os sistemas originais, pelo receio de introdução de bugs e erros, pela dificuldade em treinar os muitos funcionários antigos em um sistema que seja diferente do que já é familiar, e ainda porque os códigos-fonte não estão disponíveis, foi optado pela conteinirização do software legado em módulos docker. Não haverá curva de aprendizado, o software já cumpre as necessidades atuais da empresa, podendo ser escalado sem investimentos massivos em mais equipamentos de DataCenter. A infraestrutura atual da empresa pode ser simplificada e modernizada para simples acesso à internet, e os equipamentos que não serão mais utilizados poderão ser leiloados para interromper as perdas por depreciação. Os custos com resfriamento e segurança do DataCenter serão eliminados, e a necessidade de uma grande equipe de TI dedicada pode ser minimizada, liberando recursos para a próxima etapa.

**Etapa 3:**
- AWS AppSync
- Acesso remoto a dados
- O trabalho fisicamente restrito ao ambiente da empresa limita o crescimento potencial da empresa. Parte da equipe de TI que era subutilizada como plantão e para instalar drivers de impressora, se estiver disposta a progredir na sua capacitação, pode ser aproveitada para escrever novos aplicativos em microsserviços que complementam as funções dos sistemas legados, em especial para permitir o acesso remoto por diferentes equipamentos, algo que os vendedores mais jovens já vinham pedindo há algum tempo. Assim se reduz o custo da subutilização do capital humano, e o custo das perdas de oportunidade causadas pela necessidade de que sempre alguém dentro do ambiente físico da empresa precisasse ser acionado.
  
## Conclusão
  
A implementação de ferramentas na empresa *Abstergo Industries tem como benefícios esperados eliminar os custos em manutenção de DataCenter, redução dos custos de licenciamento de sistema de banco de dados, aumento da disponibilidade das ferramentas de software já em utilização, e preparar a transição dos sistemas para modelos mais modernos e capazes de lidar com o crescimento esperado para os próximos anos.*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.
  
  ## Anexos
  
  - [Banco de dados relacional | Amazon Aurora para MySQL e PostgreSQL | AWS](https://aws.amazon.com/pt/rds/aurora/)
    
  - [Docker: o alicerce invisível que coloca suas aplicações para rodar em qualquer ambiente | Gustavson Barros | DIO](https://www.dio.me/articles/docker-o-alicerce-invisivel-que-coloca-suas-aplicacoes-para-rodar-em-qualquer-ambiente-6ce5c03b47f6)
    
  - https://repositorio.ucb.br:9443/jspui/bitstream/123456789/12857/1/PedroAugustoResendeTCCGradua%C3%A7ao2019.pdf
    
  - [Solução de contêiner totalmente gerenciada – Amazon Elastic Container Service (Amazon ECS) - Amazon Web Services](https://aws.amazon.com/pt/ecs/)
    
  - [APIs GraphQL e Pub/Sub com tecnologia sem servidor | AWS AppSync | Amazon Web Services](https://aws.amazon.com/pt/appsync/)
    
  
  Assinatura do Responsável pelo Projeto:
  Dirceu Amilton Müller
