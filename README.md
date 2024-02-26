# AI-AZURE-SEARCH 🔍 

### 1. Criação de Recursos no Azure: 📊 
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
### 5. Alimentando o banco de dados:

- Você pode fazer upload manual dos documentos diretamente para o Azure Blob Storage por meio do Portal do Azure.
Navegue até o contêiner específico que está sendo usado como fonte de dados para o seu projeto.
Clique em "Upload" e selecione os documentos que deseja adicionar à fonte de dados.
Usando Azure Storage Explorer:

- O Azure Storage Explorer é uma ferramenta gráfica gratuita da Microsoft que permite visualizar e interagir com recursos de armazenamento do Azure, incluindo contêineres Blob.
Você pode fazer o upload de documentos para o contêiner Blob diretamente usando o Azure Storage Explorer.
Automatização com Azure Functions:

- Você pode criar uma função do Azure que é acionada por um gatilho, como a adição de um novo documento a um determinado local de armazenamento.
Dentro da função, você pode escrever o código para processar o documento e alimentar os dados no Azure AI Search.
APIs REST do Azure Blob Storage:

- Você pode usar as APIs REST do Azure Blob Storage para automatizar o processo de upload de documentos.
Isso pode ser integrado em seus próprios aplicativos ou sistemas existentes para alimentar continuamente a fonte de dados.
Usando serviços de integração de dados do Azure:

O Azure oferece serviços de integração de dados, como o Azure Data Factory, que podem ser configurados para extrair dados de várias fontes, transformá-los conforme necessário e carregá-los no Azure Blob Storage de forma automatizada.
