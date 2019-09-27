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

See also the list of [contributors](https://github.com/ezhmd/hello-world-servlet-docker/graphs/contributors) who participated in this project.

## License

Code and documentation copyright 2019 the [Hello World Servlet Docker Project Authors](https://github.com/ezhmd/hello-world-servlet-docker/graphs/contributors). 

Hello World Servlet Docker code is licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0). Images, logos, docs, and articles in this Hello World Servlet Docker project are released under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/legalcode).

Libraries, dependencies, and tools used in this project aret tied with their own licenses respectively.
