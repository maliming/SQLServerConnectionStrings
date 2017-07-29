# SQLServerConnectionStrings
SQL Server Connection Strings.

``` XML
<?xml version="1.0"?>
<configuration>
    <connectionStrings>
      
        <add name="ConnectionStringName_LocalDB" providerName="System.Data.SqlClient"
         connectionString="Data Source=(LocalDB)\v11.0;AttachDbFileName=|DataDirectory|\DatabaseFileName.mdf;InitialCatalog=DatabaseName;Integrated Security=True;MultipleActiveResultSets=True" />
        
        <add name="ConnectionStringName_SQLEXPRESS" providerName="System.Data.SqlClient"
             connectionString="Data Source=.\SQLEXPRESS;Initial Catalog=DatabaseName;Integrated Security=True;MultipleActiveResultSets=True"  />
        
        <add name="ConnectionStringName_SQLEXPRESS_App_Data" providerName="System.Data.SqlClient"
             connectionString="Data Source=.\SQLEXPRESS;AttachDbFileName=|DataDirectory|\DatabaseFileName.mdf;Integrated Security=True;User Instance=True;MultipleActiveResultSets=True" />
        
        <add name="ConnectionStringName_SQLServer" providerName="System.Data.SqlClient"
             connectionString="Data Source=ServerName;Initial Catalog=DatabaseName;Integrated Security=False;User Id=userid;Password=password;MultipleActiveResultSets=True" />
        
        <add name="ConnectionStringName_SQLServer_Integrated_Security" providerName="System.Data.SqlClient"
             connectionString="Data Source=ServerName\InstanceName;Initial Catalog=DatabaseName;Integrated Security=True;MultipleActiveResultSets=True" />
        
        <add name="ConnectionStringName_Azure" providerName="System.Data.SqlClient"
             connectionString="Data Source=tcp:ServerName.database.windows.net,1433;Initial Catalog=DatabaseName;Integrated Security=False;User Id=username@servername;Password=password;Encrypt=True;TrustServerCertificate=False;MultipleActiveResultSets=True" />
        
        <add name="ConnectionStringName_Common" providerName="System.Data.SqlClient"
             connectionString="Data Source=(LocalDB)\v11.0;AttachDbFileName=|DataDirectory|\DatabaseFileName.mdf;InitialCatalog=DatabaseName;Integrated Security=True;MultipleActiveResultSets=True" />
        
        <add name="ConnectionStringName_Common2" providerName="System.Data.SqlClient"
             connectionString="Server=(LocalDB)\v11.0;Initial File Name=|DataDirectory|\DatabaseFileName.mdf;Database=DatabaseName;Trusted_Connection=True;MultipleActiveResultSets=True" />             
    
    </connectionStrings>
</configuration>
```
