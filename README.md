# maven-estudos
 
 1) Criação da aplicação via terminal CMD no Windows 10
 
 1.1) Verificando a versão do Maven
 ```
 mvn -version
 
 ```
 1.2) Gerando o projeto
 
 ```
 mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
 
 ```
 
 1.3) Explorando o projeto
 
 ```
 tree /f
 
 ```
 
 1.4) Editando o código da aplicação App.java no VS Code (está em my-app\src\main\java\com\mycompany\app)
  
  ```
 package com.mycompany.app;

/**
 * Hello world!
 *
 */
public class App {
    public static void main( String[] args )
    {
        System.out.println("Teste de impressao");
        
    }
}
 
 ```
 
 
