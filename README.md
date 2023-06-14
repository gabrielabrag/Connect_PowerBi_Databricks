# Connect_PowerBi_Databricks
How to Connect Power Bi with Databricks ;

Conectando PowerBi com o Databricks para consumir dados de Delta Tables no seu dashboard. 

Ao acessar PowerBi e clicar em 'Obter Dados' pesquise por databricks e aperte "conectar"
![1](https://github.com/gabrielabrag/Connect_PowerBi_Databricks/assets/108342265/bdfc15c7-aa55-4361-9a42-9a488b788d7c)

Vai abrir a seguinte tela:
![2 1](https://github.com/gabrielabrag/Connect_PowerBi_Databricks/assets/108342265/5603d745-63c4-4142-8a91-ecddf5f82ef3)

Para conseguir os dados é preciso preencher o "Nome do Host do Servidor" e o "Caminho HTTP" para pegarmos essas informações basta acessar seu portal databricks e clicar na opção "Compute" e escolher o cluster que deseja consumir os dados

![2](https://github.com/gabrielabrag/Connect_PowerBi_Databricks/assets/108342265/ba6ca841-8270-4511-a25f-f36bbf6be78c)

Role ate embaixo e click em "Advanced options" na aba "JDBC/ODBC"

![4](https://github.com/gabrielabrag/Connect_PowerBi_Databricks/assets/108342265/46319092-39a8-4a7d-ab87-5f70be1f16c5)

Pronto la você encontra o "Server Hostname" e o "HTTP Path" do cluster, basta preencher no PowerBi que estara pronto para consumir esses dados. 

![5](https://github.com/gabrielabrag/Connect_PowerBi_Databricks/assets/108342265/32a3f3ca-0e79-4c0d-89a9-4ba285f29597)








