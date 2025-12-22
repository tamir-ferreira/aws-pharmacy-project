# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22 de Dezembro de 2025  
**Empresa:** Abstergo Industries  
**Responsável:** Tamir Ferreira

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Tamir Ferreira**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos ao migrar fluxos de trabalho locais (on-premises) para a nuvem.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:** - **Nome da ferramenta:** Amazon S3 (Simple Storage Service)

-   **Foco da ferramenta:** Armazenamento de objetos e Backup de longo prazo.
-   **Descrição de caso de uso:** Substituição de servidores de arquivos físicos e storages locais. O Amazon S3 permite que a empresa elimine custos com manutenção de hardware e licenciamento de softwares de backup tradicionais. Através de políticas de ciclo de vida, os dados antigos são movidos para camadas de custo ultra baixo, garantindo economia imediata e alta durabilidade.

**Etapa 2:** - **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud) com Instâncias Reservadas

-   **Foco da ferramenta:** Computação em nuvem redimensionável.
-   **Descrição de caso de uso:** Migração dos servidores de aplicação locais para instâncias virtuais. Ao contrário do servidor físico que possui um custo fixo alto independente do uso, utilizaremos instâncias dimensionadas exatamente para a carga da empresa. Além disso, implementaremos o agendamento para desligar instâncias de teste/homologação fora do horário comercial, reduzindo o desperdício de energia e recursos.

**Etapa 3:** - **Nome da ferramenta:** AWS Client VPN

-   **Foco da ferramenta:** Conectividade segura e escalável.
-   **Descrição de caso de uso:** Implementação de acesso remoto seguro para os colaboradores da Abstergo Industries. Esta solução elimina a necessidade de investir em equipamentos de VPN físicos (appliances) caros e contratos de manutenção complexos. A empresa paga apenas pelo número de conexões ativas, facilitando o trabalho híbrido com segurança de nível corporativo e custo reduzido.

## Conclusão

A implementação de ferramentas na empresa _Abstergo Industries tem como esperado a redução drástica nos gastos com manutenção de infraestrutura local, eliminação de custos com energia elétrica para datacenters e maior agilidade na recuperação de dados_, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como o AWS Cost Explorer, para manter a governança financeira sobre os recursos em nuvem.

## Anexos

1. Documento de Arquitetura da VPC (Virtual Private Cloud).
2. Tabela de Comparação de Custos: On-Premises vs Cloud (TCO).
3. Manual de Configuração de Acesso VPN para Colaboradores.

---

**Tamir Ferreira**
