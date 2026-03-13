# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 13/03/2026
Empresa: Farmacia TLDA
Responsável: Pedro Marques Bezerra dos Santos

## Introdução

Esse relatório apresenta o processo de implementação de ferramentas na empresa Farmacia LTDA, realizado por Pedro Marques Bezerra dos Santos. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir serão descritas as etapas do projeto:

Etapa 1:
- **Amazon EC2 (Elastic Compute Cloud)**
- Redução de custos com infraestutura de seridores físicos
- A Farmacia LTDA mantniha servidores físicos locais para hospedar seus sistemas de gestõa farmacêutica (ERP, controle de estoque e dispensação de medicamentos). Com a migraçãpo para a instâncias EC2 na AWS, a empresa eliminou custos com aquisição, manutençao, energia de hardware. Utilzando instâncias do tipo *Reserved Instances* com pagamento antecipado, foi possível obet uma redução de até 72% no custo de computação em comparação com o servidores on-premises, além de ganho em escalabilidade e alta disponibilidade.

Etapa 2:
- **Amazon S3 (Simple Storage Service)**
- Armazenamento seguro e econômico de documentos e dados regulatórios
- O setor farmacêutico exige o armazenamento de grandes volumes de documentos regulatórios, laudos, notas fiscais e registros de medicamentos por longos períodos, conforme exigência da ANVISA. Com o Amazon S3, a Farmacia LTDA migrou todo esse acervo documental para a nuvem, utilizando as classes de armazenamento *S3 Intelligent-Tiering* e *S3 Glacier* para arquivos de acesso raro. Isso resultou em uma redução significativa nos custos com servidores de armazenamento local e sistemas de backup físico

Etapa 3:
- **Amazon RDS (Relational Database Service)**
- Gerenciamento otimizado do banco de dados de gestão farmacêutica
- O banco de dados responsável pelo controle de estoque, vendas e prescrições médicas da Farmacia LTDA foi migrado para o Amazon RDS com o motor MySQL. O serviço gerenciado eliminou a necessidade de um DBA dedicado para tarefas rotineiras como backups, atualizações de patches e monitoramento de performance. Com o uso de instâncias *db.t3.medium* e a funcionalidade de *Multi-AZ* para alta disponibilidade, a empresa reduziu custos operacionais e garantiu continuidade do negócio mesmo em caso de falhas, com RPO e RTO mínimos.

 ## Conclusão
A implementação de ferramentas na empresa Farmacia TLDA tem como esperado a **redução imediata de custos operacionais com infraestrutura de TI**, eliminação de gastos com hardware físico, armazenamento local e equipe técnica dedicada a tarefas rotineiras. Além disso, espera-se ganhos em **segurança, escalabilidade e conformidade regulatória** — aspectos críticos para o setor farmacêutico. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
 
- Manual de configuração das instâncias EC2 — Abstergo Industries
- Política de ciclo de vida dos buckets S3 (S3 Lifecycle Policy)
- Documento de arquitetura de banco de dados — Amazon RDS Multi-AZ
- Planilha de comparativo de custos: on-premises vs AWS (TCO Analysis)
- Relatório de conformidade ANVISA para armazenamento em nuvem
 
Assinatura do Responsável pelo Projeto:
 
Pedro Marques Bezerra dos Santos
