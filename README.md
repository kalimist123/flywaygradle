# Flyway gradle example

* H2 URL 'jdbc:h2:file:./target/foobar;AUTO_SERVER=TRUE' 

* AUTOSERVER=TRUE allows connecting to db file from other client

* Connect to created db using datagrip by using full path to h2 db file in target folder

* Run migration with `gradle flywayMigrate -i`
