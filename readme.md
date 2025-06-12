Descripción del Proyecto.

Se generaron prueba unitarias con Junit
Se generaron gestión de dependencias con Maven
Se agregaron una dependencia externa.
Se Modificó una clase principal.

- Comandos usados con Maven.

- Se generó  instalación:    mvn -v
- Se creo proyecto:    mvn archetype:generate -DgroupId=com.equipo.taskmaster -DartifactId=taskmaster DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
- Se Ejecutó pruebas  mvn test
- Limpiar y empaquetar mvn clean package
- Se Ejecutó aplicación    mvn exec:java
- Se Ejecutó con perfil    mvn exec:java -Pdev -Denv.name=Dev
- Dependencias y plugins utilizados.
- Integrantes: Ingrid Oñate - Victor Diaz - Gabriel Balbontin