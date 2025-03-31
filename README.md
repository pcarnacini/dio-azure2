# Azure Databricks - DIO

## Criando um Workspace no Azure Databricks
1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. No menu, selecione **Criar um recurso** e procure por **Azure Databricks**.
3. Clique em **Criar** e forneça as informações:
   - Grupo de Recursos.
   - Nome do workspace.
   - Região.
   - Plano de preços.
4. Clique em **Revisar + Criar** e depois **Criar**.
5. Após a implantação, acesse o workspace pelo **Azure Databricks Workspace URL**.

## Criando um Cluster
1. No **Azure Databricks Workspace**, acesse **Compute**.
2. Clique em **Criar Cluster**.
3. Forneça um nome para o cluster.
4. Escolha a versão do Databricks Runtime.
5. Selecione o tipo e quantidade de nós.
6. Clique em **Criar Cluster**.

## Criando um Notebook
1. No **Azure Databricks Workspace**, vá até **Workspace** > **Criar** > **Notebook**.
2. Defina um nome e escolha a linguagem (Python, Scala, SQL ou R).
3. Associe o notebook a um cluster ativo.

## Criando um Job
1. No menu, acesse **Jobs** e clique em **Criar Job**.
2. Forneça um nome para o job.
3. Associe um notebook ou script.
4. Defina um cluster para execução.
5. Configure a programação e clique em **Criar**.

## Importando e Manipulando Dados
1. No menu, vá até **Data** e clique em **Adicionar Dados**.
2. Escolha a origem dos dados (Azure Blob Storage, SQL Database, etc.).
3. Siga as instruções para carregar e acessar os dados no notebook.

## Configurando o Git Integration
1. Vá até **Repos** e clique em **Adicionar Repositório**.
2. Escolha entre **GitHub**, **Azure DevOps** ou outro provedor Git.
3. Insira a URL do repositório e autentique.
4. Clone o repositório para uso no workspace.

## Criando um Dashboard
1. Dentro de um notebook, execute consultas SQL.
2. Converta os resultados em gráficos interativos.
3. Salve e compartilhe o dashboard com a equipe.
