# Projeto de Website Estático na AWS com Rede de Entrega de Conteúdo

Este projeto consiste em um website estático hospedado na AWS com a implementação de serviços para garantir baixa latência, segurança e armazenamento durável.

## Arquitetura


A arquitetura utilizada inclui:

### Componentes da Arquitetura

- **Amazon Route 53**: Utilizado para configuração de DNS e roteamento de tráfego, garantindo a disponibilidade e resiliência do site.
- **Amazon CloudFront**: Rede de entrega de conteúdo (CDN) para distribuir o conteúdo do site globalmente, reduzindo a latência e melhorando a experiência do usuário.
- **Amazon Certificate Manager**: Para gerenciar certificados SSL/TLS e garantir a segurança das comunicações com criptografia.
- **Amazon CloudWatch**: Monitoramento dos recursos da AWS, permitindo acompanhar o desempenho do site e configurar alertas.
- **Amazon S3**: Armazenamento durável e escalável na nuvem para hospedar os arquivos estáticos do site, garantindo alta disponibilidade e durabilidade.

## Funcionalidades Implementadas

- **Rede de Entrega de Conteúdo (CDN)**: Garante que o conteúdo do site seja entregue com baixa latência em todo o mundo.
- **Segurança SSL/TLS**: Certificados SSL/TLS gerenciados pelo ACM para proteger as comunicações.
- **Monitoramento e Alertas**: Utilização do CloudWatch para monitorar métricas e configurar alertas em caso de problemas.
- **Armazenamento Durável**: Os arquivos estáticos do site são armazenados de forma durável e escalável no Amazon S3.

Este projeto visa fornecer um website estático com alto desempenho, baixa latência, segurança e armazenamento durável, utilizando os serviços da AWS de forma integrada e eficiente.

Para mais detalhes sobre a arquitetura e implementação, consulte a documentação e configurações disponíveis no repositório do projeto.

---

Este README foi elaborado com base na arquitetura e funcionalidades do projeto de website estático na AWS com rede de entrega de conteúdo, segurança e armazenamento durável.
