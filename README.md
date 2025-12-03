# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 03 de dezembro de 2025
**Empresa:** Abstergo Industries
**Responsável:** Igor dos Santos Coelho

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Igor dos Santos Coelho**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:**

- **Nome da ferramenta:** AWS Compute Optimizer
- **Foco da ferramenta:** Otimização de recursos computacionais (Right-sizing).
- **Descrição de caso de uso:** Utilização de aprendizado de máquina para analisar o histórico de uso das instâncias EC2. A ferramenta identifica instâncias superdimensionadas (ex: servidores com muita CPU ociosa) e recomenda tipos de instâncias menores e mais baratas, garantindo que a empresa pague apenas pelo que realmente consome sem perder performance.

**Etapa 2:**

- **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Otimização de custos de armazenamento.
- **Descrição de caso de uso:** Configuração nos buckets S3 para mover dados automaticamente entre camadas de acesso. Arquivos acessados com frequência permanecem na camada padrão, enquanto logs antigos ou backups raramente acessados são movidos automaticamente para camadas de "Archive" (muito mais baratas), eliminando a necessidade de gerenciamento manual e reduzindo a fatura de storage.

**Etapa 3:**

- **Nome da ferramenta:** AWS Savings Plans
- **Foco da ferramenta:** Modelo de preços com descontos por compromisso.
- **Descrição de caso de uso:** Análise do consumo base da infraestrutura para aderir a um plano de economia (Compute Savings Plans). Ao se comprometer com um uso constante de computação (medido em $/hora) por um período de 1 ano, a empresa obtém descontos de até 66% em comparação às taxas On-Demand, aplicáveis a EC2, Fargate e Lambda.

## Conclusão

A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado **a redução significativa de desperdícios em computação e armazenamento, além da previsibilidade financeira**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Relatório de Recomendações do AWS Compute Optimizer (PDF)
- Estimativa de economia com S3 Intelligent-Tiering (Planilha .xlsx)
- Comparativo: On-Demand vs. Savings Plans (Gráfico)

**Assinatura do Responsável pelo Projeto:**

Igor dos Santos Coelho
