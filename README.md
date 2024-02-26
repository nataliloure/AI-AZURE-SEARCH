# AI-AZURE-SEARCH

### 1. Criação de Recursos no Azure:
Faça login no portal do Azure em https://portal.azure.com.
Clique no botão "+ Criar um recurso" no painel esquerdo.
Procure por "Azure AI Search" na caixa de pesquisa e selecione a opção correspondente.
Clique em "Criar" para iniciar o processo de criação do recurso.
Preencha os detalhes necessários, como assinatura, grupo de recursos, nome do serviço, localização e nível de preço.
Após a validação bem-sucedida, clique em "Revisar + criar" e, em seguida, em "Criar" para criar o recurso.
### 2. Configuração do Índice:
Após a criação do recurso Azure AI Search, navegue até o recurso no portal do Azure.
No painel de navegação à esquerda, clique em "Índices" e, em seguida, em "+ Adicionar índice".
Preencha os detalhes do índice, como nome, campos, tipos de dados, etc.
Certifique-se de incluir todos os campos relevantes para os dados hospitalares.
Configure os atributos dos campos conforme necessário.
Clique em "Criar" para finalizar a criação do índice.
### 3. Configuração da Fonte de Dados (Azure Blob Storage):
No portal do Azure, no recurso Azure AI Search, acesse a seção "Importar dados".
Selecione "Azure Blob Storage" como a fonte de dados.
Preencha os detalhes da conexão com o Azure Blob Storage, como nome da conta de armazenamento, chave de acesso, etc.
Escolha o container onde os dados estão armazenados.
Mapeie os campos da fonte de dados para os campos do índice que você criou anteriormente.
Execute o processo de importação para trazer os dados do Blob Storage para o índice.
### 4. Execução do Projeto:
Após configurar o índice e importar os dados, seu projeto de conexão com o Azure Blob Storage está pronto para uso.
Acesse a interface de consulta do Azure AI Search para começar a pesquisar e analisar os dados.
Experimente diferentes consultas e filtros para extrair insights úteis.
Monitore o desempenho do seu projeto e otimize conforme necessário.
Seguindo esses passos, você poderá criar e configurar um projeto de busca de dados hospitalares conectado ao Azure Blob Storage usando o Azure AI Search.
