[The detailed information of the code usage with screenshots see in Info.docx]

In database exist table Provider where we can change provider settings or add new provider for all files in some folder
Shemas for each provider stored at own xml file, which can be modified at any moment. 
Default schema was generated by bcp tool https://docs.microsoft.com/en-us/sql/relational-databases/import-export/xml-format-files-sql-server?view=sql-server-ver15
Exist store procedure [spReadFils] which make import data from all files in specified dirrectory to table

Database dump FileReader.bak
Sample files/xml schema by providers see in nested folders
