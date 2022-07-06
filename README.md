# Datafi CLI
```
dfcli dataset -h
NAME:
   dfcli dataset - Configures datasets

USAGE:
   dataset [options] command

COMMANDS:
   check    
   add      
   update   
   help, h  Shows a list of commands or help for one command

OPTIONS:
   --configPath value      Path to the edge server config file (default: "./config.yaml")
   --endpoint value        Endpoint for the edge server
   --keyPath value         Path to the edge server key file (default: "./key.txt")
   --mode value            Mode of operation: dev, prod (default: "prod")
   --name value            Name of dataset
   --pointOfContact value  Email of the point of contact
   --type value            Dataset type: databricks, msdynamics, mssql, mysql, oracle, postgres, s3select, salesforce, snowflake, synapse
                           
   --account value         Param for salesforce, snowflake
   --address value         Param for mysql, postgres
   --bucket value          Param for s3select
   --clientID value        Param for msdynamics, salesforce
   --clientSecret value    Param for msdynamics, salesforce
   --dbname value          Param for mssql, mysql, postgres, snowflake, synapse
   --host value            Param for databricks
   --password value        Param for mssql, mysql, oracle, postgres, salesforce, snowflake, synapse
   --path value            Param for databricks
   --port value            Param for mssql, oracle, synapse
   --refreshToken value    Param for msdynamics
   --server value          Param for mssql, oracle, synapse
   --service value         Param for oracle
   --tenantDomain value    Param for msdynamics
   --token value           Param for databricks
   --username value        Param for mssql, mysql, oracle, postgres, salesforce, snowflake, synapse
   --help, -h              show help (default: false)

```
