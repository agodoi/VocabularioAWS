# Vocabulário AWS

## Alta Disponibilidade:
São multi data center isolados fisicamente, porém interconectados. Serviços relacionados: Amazon Elastic Load Balancing (ELB), Amazon Route 53, Amazon RDS Multi-AZ, Amazon S3 Cross-Region Replication, Amazon CloudWatch Alarms, Amazon EC2 Auto Scaling, Amazon S3 Object Lifecycle Policies, AWS Global Accelerator, Amazon Aurora Global Database e Zonas de Disponibilidade (AZs).

## Resiliência:
É a capacidade de um sistema ou aplicação de continuar funcionando de maneira confiável e eficaz mesmo diante de falhas ou interrupções. Serviços que tentam garantir isso: Multi-AZ (regiões), Load Balance (ALB), AutoScalling, backups S3 e monitoramentos via alertas.

## Conectividade:
Capacidade de interligar recursos, serviços e instâncias em uma infraestrutura na nuvem, permitindo a comunicação eficiente e segura entre eles. Serviços relacionados: VPC, Internet Gateway e NAT, Gateway de cliente VPN, Direct Connect, ALB, Security Groups, Network ACL, Private Link, CloudFront.

## Elasticidade:
Permite que os recursos de computação, armazenamento e rede se expandam ou contraiam dinamicamente com base na carga de trabalho em tempo real, garantindo que os aplicativos mantenham um desempenho adequado, mesmo durante picos de tráfego. Serviços relacionados: Auto Scalling, ELB, RDS Auto Scalling, EBS, AWS Lambda.

## Failover:
É o processo de transferir automaticamente o tráfego e as operações de um recurso ou serviço de uma instância primária para um ambiente de backup (instância secundária) quando ocorre uma falha no ambiente principal e assim, os usuários e as aplicações continuem funcionando sem interrupções significativas. Serviços relacionados: Multi-AZ Deployment, ELB, Amazon RDS Multi-AZ, AWS Global Accelerator e Route 53 Health Checks.

## Segurança:
Refere-se à implementação de medidas e práticas que protegem os dados, sistemas e recursos dos clientes, garantindo a confidencialidade, integridade e disponibilidade das informações. Serviços relacionados: IAM, criptografia, AWS CloudTrail, GuardDuty, firewall, VPC, Security Groups, KMS, AWS Shield, Amazon Macie.

## Auditoria:
É o processo de monitoramento e registro das atividades e eventos que ocorrem em uma conta ou ambiente da AWS, rastreia quem fez o quê, identifica atividades suspeitas e manter a visibilidade sobre as operações realizadas dentro da infraestrutura, identifica vulnerabilidades. Serviços: Amazon CloudTrail, Amazon CloudWatch, Amazon GuardDuty, AWS Config, Amazon Inspector e IAM.

## Acesso Global:
Refere-se à capacidade de permitir que os usuários acessem e interajam com recursos e serviços da AWS em diferentes regiões geográficas, proporcionando uma experiência consistente e de alta qualidade em todo o mundo. Isso é importante para empresas e aplicativos que possuem uma presença global e desejam oferecer serviços a usuários em diferentes partes do mundo. Serviços: Amazon CloudFront, Amazon Route 53, AWS Global Accelerator, AWS Regional Edge Caches, Amazon S3 e o Amazon DynamoDB (que possuem opções de replicação global), Arquitetura Multi-Região (usuários possam acessar a aplicação a partir da região mais próxima, reduzindo a latência e melhorando a experiência do usuário).

## Integração:
É o processo de conectar e sincronizar diferentes componentes, serviços ou sistemas para permitir que eles funcionem juntos de maneira harmoniosa e eficiente. Serviços: Amazon API Gateway, AWS Lambda, AWS Step Functions, Amazon SQS e Amazon SNS, AWS Data Pipeline, AWS App Integration Services (Amazon AppFlow e Amazon EventBridge), AWS Direct Connect, VPN, AWS Glue para ETL (Extração, Transformação e Carga) e Amazon Redshift para análise de dados.

## Auto Scalling:
Permite ajustar automaticamente a capacidade de recursos computacionais, como instâncias de VM, em resposta às demandas de tráfego ou carga de trabalho. O objetivo principal é garantir que você tenha o número certo de recursos disponíveis em momento de picos para atender à demanda, otimizando o desempenho e minimizando os custos operacionais. Serviços relacionados: Amazon EC2, Auto Scaling Groups, ELB, Amazon CloudWatch, Amazon RDS, ECS (Elastic Container Service) Amazon EKS (Elastic Kubernetes). Service.
