# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 29/07/2025
Empresa: Abstergo Industries 
Responsável: Genildon Barreto

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Genildon Barreto. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (Simple Storage Service)
- Com foco em armazenamento de objetos escalável, durável e de baixo custo.
- Utilizar o S3 como um repositório centralizado para documentos e dados que precisam ser compartilhados com outras empresas e farmácias. Isso elimina a necessidade de infraestrutura VPN ou FTP complexa e cara, substituindo-a por acesso seguro e simples via S3.

Etapa 2: 
- AWS Lambda
- Com foco em execução de código sem provisionar ou gerenciar servidores, pagando apenas pelo tempo de execução.
- Eliminar custos de servidores ociosos, paga-se apenas por computação ativa.

Etapa 3: 
- Amazon RDS (Relational Database Service)
- Bancos de dados relacionais gerenciados pela AWS, com escalabilidade e alta disponibilidade.
- Eliminar custos de hardware de servidor de banco de dados, manutenção do SO, licenças (para certas engines), e grande parte do custo operacional de DBAs. Pagando-se por instância e uso.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado Redução de Custos Operacionais*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
<img src="https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/images/TUT_Lambda_1.png">
<img src="https://d2908q01vomqb2.cloudfront.net/d435a6cdd786300dff204ee7c2ef942d3e9034e2/2021/01/19/image001-1.jpg">

| Característica de Custo | Antes (On-Premise) | Depois (AWS) | Benefício com AWS |
|---|---|---|---|
| Armazenamento (S3) | Custos de Hardware de Storage Anuais: R$ 50.000) | Custo de Armazenamento por Uso (S3): R$ 5.000/ano (hipotético) | Redução de R$ 45.000/ano em hardware e manutenção.
| Computação (Lambda) | Custos de Servidores Ociosos: R$ 30.000/ano | Custo por Execução (Lambda): R$ 3.000/ano (hipotético) | Eliminação de R$ 27.000/ano em servidores subutilizados.
| Banco de Dados (RDS) | Custos de Hardware de Servidor de DB, Licenças, Manutenção de SO, DBA: R$ 80.000/ano | Custo de Instância e Uso (RDS): R$ 15.000/ano (hipotético) | Redução de R$ 65.000/ano em infraestrutura e gerenciamento de DB.
| Custos de Energia Estimados | R$ 10.000/ano | R$ 0 (transferido para AWS) | Redução de R$ 10.000/ano em consumo de energia local.
| Manutenção e Operação | Equipe de TI para Manutenção: R$ 40.000/ano | Menor Necessidade de Manutenção (AWS Gerenciado): R$ 5.000/ano (hipotético) | Redução de R$ 35.000/ano em despesas com equipe e horas de trabalho.
| Total Anual Estimado | R$ 210.000 | R$ 28.000 | Economia Potencial Anual: R$ 182.000


Assinatura do Responsável pelo Projeto:

Genildon Barreto