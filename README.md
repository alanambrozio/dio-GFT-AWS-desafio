# dio-GFT-AWS-desafio

## RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

- Data: 20/07/2025
- Empresa: Abstergo Industries
- Responsável: Alan César Ambrozio

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries,  realizado por  Alan César Ambrozio. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 Auto Scaling
- Utilizar o escalonamento de instâncias EC2 automaticamento com base na demanda.  
- O EC2 Auto Scaling garante que a empresa tenha apenas a capacidade de computação necessária no momento, adicionando ou removendo instâncias automaticamente. Dessa maneira quando ao empresa estiver precisando de uma maior demanda por sistemas o sistemas será capaz de fornecer. Em momentos que não é nescessario muita demanda ele reduzirá as instancias. Dessa forma é possivel economizar e ao mesmo tempo garantir que não ocorrerá problemas ao atender os clientes, mesmo com um alto volume de solicitações.

Etapa 2:
- Amazon S3 (com Tiering Inteligente)
- Reduzir custos de armazenamento de dados.
- A empresa lida com um grande volume de dados, incluindo registros de pedidos, faturas, informações de clientes, dados de inventário e backups. Ao utilizar o Tiering Inteligente Amazon S3 os dados serão salvos automaticamente no tipo de armazenamento mais vantajoso. Dados como de backups que são acessados raramente vão ficar em um armazenamento mais barato, outros dados que são acessados diariamente serão armazenados em dependencias mais ágeis para facilidade de acesso dessas informações. 

Etapa 3:
- Amazon Relational Database Service (RDS)
- Otimizar custos e esforços de gerenciamento de bancos de dados relacionais.
- Migrando bancos de dados de sistemas de pedidos, cadastro de produtos ou histórico de vendas para o Amazon RDS, a Abstergo Industries pode reduzir drasticamente custos como: Hardware, licenças de software, pessoal e manutenção. O RDS automatiza tarefas como provisionamento de hardware, patching de software, backups e escalabilidade, permitindo que a equipe se concentre em atividades mais estratégicas.


## Conclusão
A implemetação de ferramentas na empresa Abstergo Industries tem como esperado a otimização de recursos de computação, a redução de custos com armazenamento de dados e a simplificação do gerenciamento de bancos de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
- [EC2](https://aws.amazon.com/pt/ec2/autoscaling/) - Acessado em 20/07/2025
- [RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) - Acessado em 20/07/2025
- [S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html) - Acessado em 20/07/2025


Assinatura do Responsável pelo Projeto:
Alan César Ambrozio
