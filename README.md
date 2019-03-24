# Hello World Servlet Docker

This template is a simple Java Servlet starter using Docker.

## Running

1. Download [Servlet Api JAR](https://mvnrepository.com/artifact/javax.servlet/servlet-api) and put inside `./webapps/mysite/src/jar`.

1. Run following commands
    ```sh
    # Make directory for classes destination
    mkdir ./webapps/mysite/WEB-INF/classes

    # Compile Java files
    javac -cp ./webapps/mysite/src/jar/*.jar -d ./webapps/mysite/WEB-INF/classes ./webapps/mysite/src/*.java

    # Run Docker
    docker-compose up -d
    ```
1. Open the pages in web browser

    http://localhost:8888/mysite/

    http://localhost:8888/mysite/hello-world