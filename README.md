# Exemplo Micro Serviço Spring boot com spark


 
### Tecnologia utilizada

* Java
* Spring boot
* Spark
* Maven

### Como rodar a aplicação

Para rodar a aplicação é necessário Java 8 e Maven 3, atendendo este requisito executar os passos a seguir

1. baixar o projeto no git: git clone https://github.com/rodrigolsoares/exemplo-spring-spark.git
2. abrir o prompt de comando, e ir até o diretório raiz do código fonte: ./exemplo-spring-spark
3. Executar o comando mvn package
4. Apos rodar o maven, ir até o diretório ./exemplo-micro-service-spring-boot/target
5. Executar o comando java -jar exemplo-micro-service-spring-boot-0.0.1-SNAPSHOT.jar
6. abrir o navegador e executar a url de acesso a aplicação


### Url de acesso da aplicação

http://127.0.0.1:8080/wordcount

### Parametro de entrada
{"key":"words","value":"Russia|Argentina|Brasil|China|EUA|Argentina|Chile|Brasil|Japão|Brasil":""}

### Resultado
{
    "EUA": 1,
    "Russia": 1,
    "China": 1,
    "Argentina": 2,
    "Brasil": 3,
    "Japão": 1,
    "Chile": 1
}


 



