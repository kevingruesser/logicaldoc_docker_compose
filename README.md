# logicaldoc_docker_compose
LogicalDoc DMS-System

The LogicalDOC image uses environment variables that allow to obtain a more specific setup.

LDOC_MEMORY: memory allocated for LogicalDOC expressed in MB (default is 2000)
DB_ENGINE: the database type, possible vaues are: mysql(default), mssql, oracle, postgres
DB_HOST: the database server host (default is 'mysql-ld')
DB_PORT: the database communication port (default is 3306)
DB_NAME: the database name (default is 'logicaldoc')
DB_INSTANCE: some databases require the instance specification
DB_USER: the username (default is 'ldoc')
DB_PASSWORD: the password (default is 'changeme')
DB_MANUALURL: must be true when using DB_URL (default is 'false')
DB_URL: the jdbc url to connect to the database (remember to set DB_MANUALURL to 'true')
