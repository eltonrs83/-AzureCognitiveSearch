# -AzureCognitiveSearch
Criar um mecanismo de avaliação sensorial para incluir em site ou programa.
Entrar no Azure - Azure AI Search e criar novo recurso. Criar nome do recurso e selecionar o recurso básico.
Entrar no Azure Ai Services - seleciona Resouce Group, east US, criar nome, princing tier: standard S0, marcar check box. Clica review + create.
Entrar em Storage Accounts - Criar - seleciona o resource grupo criado na etapa anterior - nome da storage (criar um conforme as diretrizes informadas no site) - região US - Performance (standard) - Redundancy (LRS) - review e create.
Entra na Storage criada e clica em configurações no menu esquerdo - Allow Blob anonymous acess (seleciona enabled) - Save
Data Storage - Containers - + container - New Container (cria nome) - entra na pasta onde tem os arquivos 
Criado o mecanismo de busca, rescurso de IA, storage account
Entra no AI Search - clica no mecanismo criado -  import dada (menu superior) - seleciona o arquivo carregado - ao entrar nele poderá realizar pesquisas - posso buscar por sentimento negativo (search=sentiment:'negative'
Finalidade foi criar um serviço de IA, fazer link com a automação, direcionar para um repositório. Posso implementar dentro de um software para ter a consulta de uma maneira mais prática.
