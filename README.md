ACME Travel Data Model Project
==============================

This project will build a data model JAR file for importing into JBoss BPM Suite as
an external data model.


Install on your machine
-----------------------
1. [Download and unzip.](https://github.com/effectivebpmwithjbossbpm/chapter-4-acme-travel-data-model/archive/master.zip)

2. Build the data model:

  ```
  $ cd chapter-4-acme-travel-data-model

  $ mvn clean package
  ```

The resulting `target/acmeDataModel-1.0.jar` file can be imported for use in your
JBoss BPM projects, see chapter 4 for details.
 
