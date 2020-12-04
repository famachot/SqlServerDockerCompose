# Sql Server Docker Compose
Creates a container running SQL Server via Docker Compose


# Instructions for use

Clone the repo down and navigate to it<br>
Create the sapassword.env file and enter something similar to:-<br>
MSSQL_SA_PASSWORD=MY_SA_PASSWORD<br>
Now run:-<br>
docker-compose up -d


Se puede usar con el cliente de Microsoft SSMS que pueden descargar desde (aqui)[https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15]


Server Name: localhost, 15789
Login: sa
Password: (El que se haya especificado en el archivo)