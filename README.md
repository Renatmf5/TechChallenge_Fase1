# Projeto Tech Challenge Fase 1 - Entrega Final

Este repositório contém a entrega final do **Projeto Tech Challenge Fase 1**, desenvolvido pelo grupo composto por:
- **Renato Moreno Ferreira** - rm358385
- **Everton [Sobrenome]**

## Descrição do Projeto

O objetivo deste projeto foi desenvolver uma API integrada com a base de dados do [Vitibrasil](http://vitibrasil.cnpuv.embrapa.br), oferecendo módulos de captação, tratamento e análise dos dados. O armazenamento dos dados foi realizado em um Data Lake na AWS S3. Além disso, foi implementado um módulo básico de machine learning para treinamento e predição de modelos, utilizando a base explorada.

### Funcionalidades:
- Captação e tratamento de dados da base do Vitibrasil.
- Armazenamento dos arquivos processados na AWS S3.
- Treinamento de um modelo básico de machine learning (regressão linear simples) para predição de alguns dados da base.

### Evoluções Futuras:
Nosso plano é expandir as funcionalidades da inteligência artificial e aprimorar o sistema de análise de dados com as seguintes etapas:

1. **Ampliar a cobertura dos modelos**: Expandir o treinamento e predição para todas as categorias de dados disponíveis.
2. **Otimização de Modelos**: Otimizar os hiperparâmetros dos modelos de regressão e explorar métodos adicionais, como XGBoost.
3. **Integração de Dados Externos**: Incorporar dados externos para aumentar a profundidade das análises. Exemplos de dados externos:
   - **Dados climáticos**: Correlacionar a produção agrícola com dados climáticos para explicar melhor as variações de produtividade.
   - **Dados macroeconômicos**: Correlacionar dados de importação/exportação com indicadores econômicos dos países parceiros para uma análise mais rica.
   - **Dados de marketing**: Relacionar as vendas de produtos com campanhas de marketing para entender melhor os resultados comerciais.

## Estrutura Técnica

A seguir, detalhamos os três repositórios que compõem a estrutura do projeto.

### 1. Repositório de Infraestrutura e Deploy

Este repositório contém as configurações de deploy e a infraestrutura do projeto, criada com AWS CDK. Ele inclui pipelines para gerenciar o deploy da aplicação na AWS.

- [Repositório de Infraestrutura e Deploy no GitHub](https://github.com/Renatmf5/aws-cdk-ml-infra-pipelines)

### 2. Repositório da API FastAPI

Aqui estão o código da API desenvolvida em FastAPI e a documentação detalhada do projeto. A API integra-se com os dados do Vitibrasil, realizando o processamento e expondo endpoints para consumo.

- [Repositório da API no GitHub](https://github.com/Renatmf5/API-FastApi-WebScraping)

### 3. Repositório da Interface Web (Next.js)

Este repositório contém o código da interface gráfica desenvolvida em Next.js. A interface interage diretamente com a API, proporcionando uma experiência amigável ao usuário.

- [Repositório da Interface Web no GitHub](https://github.com/Renatmf5/nextjs-app-interface)

## Gerenciamento do Projeto

O progresso do projeto, com commits e branches, está sendo acompanhado e documentado através do GitHub Projects.

- [Acesse o Projeto no GitHub](https://github.com/users/Renatmf5/projects/1)