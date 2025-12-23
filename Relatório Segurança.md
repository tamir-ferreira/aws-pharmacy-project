# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 23 de dezembro de 2025
**Empresa:** Abstergo Industries
**Responsável:** Tamir Ferreira

## ## Introdução

Este relatório apresenta o processo de implementação de ferramentas de segurança na empresa **Abstergo Industries**, realizado por Tamir Ferreira. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto com os serviços da AWS, com a finalidade de realizar o monitoramento proativo e aumentar a segurança na empresa.

## ## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança fundamentais para a integridade da infraestrutura Cloud. A seguir, serão descritas as etapas da implementação:

### 1. Governança e Auditoria com AWS CloudTrail

-   **Ação:** Ativação do CloudTrail para registo de logs de API em todas as regiões.
-   **Finalidade:** Monitorizar "quem fez o quê" na conta. Essencial para identificar ações não programadas, como o desligamento de instâncias ou alterações em permissões.
-   **Resultado:** Capacidade total de auditoria e rastreabilidade de eventos de gestão.

### 2. Postura de Segurança com AWS Trusted Advisor

-   **Ação:** Configuração de alertas para o pilar de Segurança, com foco em MFA (Multi-Factor Authentication).
-   **Finalidade:** Verificar se a conta raiz e utilizadores administrativos possuem camadas extras de proteção.
-   **Resultado:** Redução de vulnerabilidades críticas relacionadas com o acesso à consola de gestão.

### 3. Análise de Comportamento com CloudTrail Insights

-   **Ação:** Implementação de deteção de anomalias baseada em aprendizagem automática.
-   **Finalidade:** Apresentar de forma gráfica comportamentos suspeitos ou picos de utilização de APIs que fujam do padrão normal de operação.
-   **Resultado:** Identificação precoce de possíveis ataques ou erros de automação antes que causem impacto financeiro.

## ## Conclusão

A implementação destas medidas garante que a **Abstergo Industries** possui agora uma base sólida de monitorização e proteção. Com a utilização combinada do CloudTrail e do Trusted Advisor, a empresa não só cumpre requisitos de conformidade, como também adota uma postura proativa na mitigação de riscos de segurança na AWS.
