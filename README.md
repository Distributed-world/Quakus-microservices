# Quakus-microservices
###### mvn archetype:generate "-DgroupId=org.mvi.quarkus.microservices" "-DartifactId=quarkus-microservices" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DarchetypeVersion=1.4" "-DinteractiveMode=false"
###### add/change in pom <packaging>pom</packaging>
###### go in to folder
###### mvn clean install
###### mvn -U io.quarkus:quarkus-maven-plugin:create -DprojectGroupId=org.mvi.quarkus.microservices -DprojectArtifactId=number-service -DclassName="org.mvi.quarkus.microservices.number.NumberResource" -Dpath="/api/numbers" -Dextensions="resteasy-jsonb, smallrye-openapi"
###### mvn -U io.quarkus:quarkus-maven-plugin:create -DprojectGroupId=org.mvi.quarkus.microservices -DprojectArtifactId=book-service -DclassName="org.mvi.quarkus.microservices.number.BookResource" -Dpath="/api/books" -Dextensions="resteasy-jsonb, smallrye-openapi"

