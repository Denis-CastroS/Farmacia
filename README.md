# Farmacia
Redução de Custo em farmácia com AWS
RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 12 de abril de 2026
Empresa: Abstergo Industries
Responsável: Denis Silva

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Frmácias Pará, realizado por Denis Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimizar a infraestrutura da plataforma virtual da farmácia.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

Amazon S3 (Simple Storage Service)

Armazenamento de Objetos (Object Storage)

Caso de Uso: Armazenamento de imagens de produtos, bulas em PDF e documentos regulatórios da farmácia. A utilização do S3 permite eliminar a necessidade de servidores de arquivos caros, utilizando políticas de ciclo de vida (como o S3 Intelligent-Tiering) para reduzir custos automaticamente conforme o padrão de acesso aos dados.

Etapa 2:

Amazon DynamoDB

Banco de Dados NoSQL (Chave-Valor)

Caso de Uso: Gestão do catálogo de medicamentos e controle de estoque em tempo real. Por ser um serviço serverless, a farmácia paga apenas pelo que utiliza (on-demand), evitando custos fixos de instâncias de banco de dados ligadas 24/7 e garantindo alta performance com latência de milissegundos para consultas de preços.

Etapa 3:

Amazon EC2 com instâncias Spot

Computação em Nuvem Flexível

Caso de Uso: Processamento de logs de vendas e geração de relatórios diários de fechamento de caixa. Ao utilizar instâncias Spot para tarefas que podem ser interrompidas ou processamento em lote, a empresa consegue uma redução de custos de até 90% em comparação às instâncias sob demanda, mantendo a eficiência do processamento de dados.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução drástica de gastos com infraestrutura física e a eliminação de subutilização de recursos através do modelo de pagamento por uso (pay-as-you-go), o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como o AWS Lambda, que possam melhorar ainda mais os processos da empresa.

Anexos
* [Manual de políticas de ciclo de vida do Amazon S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)
* [Dashboard de monitoramento de custos (AWS Cost Explorer)](https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/)
* [Guia de boas práticas para instâncias Spot](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/spot-best-practices.html)

Denis Silva
