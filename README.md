# Vocabulario AWS

## Disponibilidade:
São multi data center isolados fisicamente, porém interconectados

## Resiliência:
É a capacidade de um sistema ou aplicação de continuar funcionando de maneira confiável e eficaz mesmo diante de falhas ou interrupções. Serviços que tentam garantir isso: Multi-AZ (regiões), Load Balance (ALB), AutoScalling, backups S3 e monitoramentos via alertas.

## Conectividade:
Capacidade de interligar recursos, serviços e instâncias em uma infraestrutura na nuvem, permitindo a comunicação eficiente e segura entre eles. Serviços relacionados: VPC, Internet Gateway e NAT, Gateway de cliente VPN, Direct Connect, ALB, Security Groups, Network ACL, Private Link.

## Elasticidade:
Permite que os recursos de computação, armazenamento e rede se expandam ou contraiam dinamicamente com base na carga de trabalho em tempo real, garantindo que os aplicativos mantenham um desempenho adequado, mesmo durante picos de tráfego. Serviços relacionados: Auto Scalling, ELB, RDS Auto Scalling, EBS, AWS Lambda.

## Failover:
É o processo de transferir automaticamente o tráfego e as operações de um recurso ou serviço de uma instância primária para um ambiente de backup (instância secundária) quando ocorre uma falha no ambiente principal e assim, os usuários e as aplicações continuem funcionando sem interrupções significativas. Serviços relacionados: Multi-AZ Deployment, ELB, Amazon RDS Multi-AZ, AWS Global Accelerator e Route 53 Health Checks.

