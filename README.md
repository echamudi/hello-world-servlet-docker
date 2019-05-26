# Hello World Servlet Docker

A simple Java Servlet starter template using Docker

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
    
## Authors

* **Ezzat Chamudi** - [ezhmd](https://github.com/ezhmd)

## Licenses

The code released under [MIT License](https://spdx.org/licenses/MIT.html). 

Libraries, dependencies, and tools used in this project tied with their own licenses respectively.
