# Aula 4 

 Com base nos requisitos da empresa foi escolhido o modelo nuvem híbrida.

## Vantagens: 

Flexibilidade da nuvem pública, somada à garantia de segurança de uma nuvem privada, usa a pública para cargas intensivas temporárias e permite alocar dados sensíveis na nuvem privada, alta flexibilidade e alinhamento com compliance/regulamentação, é possível usar a nuvem pública apenas nos momentos de pico de uso, reduzindo o risco de sobrecarga, aplicações podem escalar automaticamente usando recursos elásticos, enquanto sistemas mais críticos permanecem isolados, paga-se pela nuvem pública somente quando utilizada, evitando investimentos excessivos em infraestrutura dedicada, se uma parte da infraestrutura falhar, a outra pode assumir temporariamente as operações críticas.

## Desafios:

Complexidade de integração, gerenciamento e orquestração dos dois ambientes, maior exigência técnica e de governança, diferenças em APIs, sistemas operacionais e arquiteturas dificultam compatibilidade total, exige monitoramento centralizado e padronização entre ambientes para garantir visibilidade, fluxos de dados entre nuvens precisam ser criptografados e auditados, A nuvem híbrida pode reduzir custos se bem planejada, mas custos com integração, licenciamento e conectividade privada (VPN, links dedicados) podem elevar o investimento.


## Exemplos de provedores:

| Modelo de Nuvem | Provedor                        | País/Região     | Descrição Resumida                                                                | Principais Características                                    |
| --------------- | ------------------------------- | --------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| **Pública**     | **Amazon Web Services (AWS)**   | Global          | Maior provedor de nuvem pública do mundo, com ampla gama de serviços.             | Alta escalabilidade, pay-per-use, suporte multirregional      |
| **Pública**     | **Microsoft Azure**             | Global          | Plataforma da Microsoft com forte integração com sistemas corporativos (Windows). | Integração com Active Directory, suporte híbrido e compliance |
| **Pública**     | **Google Cloud Platform (GCP)** | Global          | Foco em IA, big data e computação escalável.                                      | Desempenho avançado, forte em analytics e machine learning    |
| **Privada**     | **EVEO Cloud**                  | Brasil          | Infraestrutura própria no Brasil, com foco em segurança, compliance e suporte.    | Certificações ISO, ambientes dedicados, personalizável        |
| **Privada**     | **HostDime Brasil**             | Brasil / EUA    | Data centers com foco em alta segurança, compliance e nuvem privada gerenciada.   | Serviços de backup, firewall gerenciado, DDoS protection      |
| **Privada**     | **VMware Cloud Foundation**     | Global          | Plataforma para criar nuvens privadas sob medida com gerenciamento centralizado.  | Altamente personalizável, ideal para ambientes corporativos   |
| **Híbrida**     | **Microsoft Azure Stack**       | Global          | Extensão local da nuvem Azure para cenários híbridos.                             | Mesma experiência Azure no data center local                  |
| **Híbrida**     | **AWS Outposts**                | Global          | Infraestrutura da AWS instalada localmente para uso híbrido.                      | Baixa latência, gerenciamento unificado com AWS cloud         |
| **Híbrida**     | **Equinix Cloud Exchange**      | Global / Brasil | Plataforma de interconexão entre múltiplas nuvens públicas e privadas.            | Alta disponibilidade, conectividade privada segura            |
| **Híbrida**     | **Google Anthos**               | Global          | Gerencia cargas em GCP, nuvens de terceiros ou on-premises.                       | Kubernetes nativo, multi-cloud, compliance integrada          |





## Tabela comparativa:
| Requisito da Empresa                   | Nuvem Pública                            | Nuvem Privada                       | Nuvem Híbrida                                |
| -------------------------------------- | ---------------------------------------- | ----------------------------------- | -------------------------------------------- |
| Alta segurança (dados sensíveis)       | Control limitado                         | Excelente                           | Excelente em privada                         |
| Alta demanda em promoções (e-commerce) | Escalabilidade alta                      | Limitada                            | Excelente via pública                        |
| Redução de custos TI                   | Baixo custo                              | Alto custo                          | Otimizado (paga uso)                         |
| Flexibilidade / expansão futura        | Alta flexibilidade                       | Limitada                            | Alta flexibilidade                           |
| **Resumo geral**                       | Boa para workloads não sensíveis e custo | Boa para dados sensíveis e controle | Combina segurança, escalabilidade e economia |
