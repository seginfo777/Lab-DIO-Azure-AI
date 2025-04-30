# 🔍 Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

Este projeto é resultado do laboratório prático oferecido pela DIO em parceria com a XP Inc., focado na utilização do Azure Cognitive Search (agora conhecido como Azure AI Search) para realizar indexação e consulta de dados utilizando recursos de inteligência artificial. O objetivo é capacitar desenvolvedores a aplicar técnicas de busca inteligente e enriquecimento de dados utilizando os serviços cognitivos do Azure.

---

##  Conteúdo Aprendido

### 1. Introdução ao Azure Cognitive Search

- **Azure Cognitive Search** é um serviço de busca na nuvem que permite indexar e consultar dados estruturados e não estruturados com alta performance.
- Oferece funcionalidades como:
  - Indexação de grandes volumes de dados.
  - Consultas full-text e semânticas.
  - Enriquecimento de dados com habilidades cognitivas (OCR, análise de sentimentos, extração de entidades, etc.).
- Utiliza o algoritmo de pesquisa Lucene, garantindo velocidade e precisão nas buscas. :contentReference[oaicite:3]{index=3}

### 2. Configuração do Ambiente

- Criação de uma conta no portal do Azure.
- Provisionamento dos seguintes recursos:
  - **Azure Cognitive Search**: gerencia a indexação e pesquisa dos documentos.
  - **Azure AI Services**: fornece as funcionalidades de IA necessárias para enriquecer os dados dos documentos com insights.
  - **Storage Account**: armazena os documentos em blob containers.

### 3. Upload dos Dados e Criação do Índice

- As avaliações de clientes (reviews) são carregadas no container de armazenamento.
- Utilização do assistente de importação de dados no portal do Azure para:
  - Selecionar o storage onde os documentos estão armazenados.
  - Definir as habilidades cognitivas que serão usadas para enriquecer os dados.
  - Criar o índice e o indexador automaticamente.

### 4. Consultas no Índice

- O Azure Cognitive Search fornece um assistente para realizar pesquisas no índice criado.
- Os resultados são retornados em JSON.
- Exemplos de consultas realizadas:
  - Filtrar resultados por localização (e.g., cidade de Chicago).
  - Pesquisar avaliações com tom negativo utilizando análise de sentimentos.

---

##  Tecnologias Utilizadas

- Microsoft Azure
- Azure Cognitive Search (Azure AI Search)
- Azure AI Services
- Azure Storage Account

---

##  Como Reproduzir o Projeto

1. Crie uma conta no [Portal do Azure](https://portal.azure.com/).
2. No portal, crie os seguintes recursos:
   - **Azure Cognitive Search**
   - **Azure AI Services**
   - **Storage Account**
3. Faça o upload dos documentos (e.g., avaliações de clientes) no blob container do Storage Account.
4. Acesse o recurso do Azure Cognitive Search e utilize o assistente de importação de dados para:
   - Conectar ao Storage Account.
   - Definir as habilidades cognitivas desejadas.
   - Criar o índice e o indexador.
5. Utilize o assistente de consultas para realizar buscas no índice criado e analisar os resultados.

---

##  Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

**Links úteis**:

- [Portal do Azure](https://portal.azure.com/)
- [Documentação oficial - Azure AI Search](https://learn.microsoft.com/en-us/azure/search/)

---
