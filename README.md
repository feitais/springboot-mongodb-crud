mvn install

java -jar target/springboot-mongodb-crud-0.0.1-SNAPSHOT.jar 

mvn spring-boot:run

localhost:8080/products/

Json Add product
{"name": "Teste",
"description": "Teste"}

response

{
    "id": 0,
    "name": "Teste",
    "description": "Teste"
}

localhost:8080/products/0

{
    "id": 0,
    "name": "Teste",
    "description": "Teste"
}

