# maven-estudos
 
 ### 1) **Criação da aplicação via terminal CMD no Windows 10**
 
 #### 1.1) **Verificando a versão do Maven**
 ```
 mvn -version
 
 ```
 #### 1.2) **Gerando o projeto**
 
 ```
 mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
 
 ```
 
 #### 1.3) **Explorando o projeto**
 
 ```
 tree /f
 
 ```
 
 #### 1.4) **Editando o código da aplicação App.java no VS Code** (está em my-app\src\main\java\com\mycompany\app)
  
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
 #### 1.5) ** Executando a fase package **
 #### Quando uma fase é fornecida para o Maven, ele executará todas as fases da sequência até a fase que foi fornecida. ####
 
 ```
 mvn package
 
 ```
 
 #### 1.6) ** Executando a aplicação compilada e empacotada - arquivo JAR **
 
#### Depois que executamos o “mvn package”, podemos observar que o Maven criou uma nova pasta chamada de “target” dentro da pasta “my-app”. Explorando a pasta “target”, podemos ver o arquivo: my-app-1.0-SNAPSHOT.jar ####
 
 ```
 java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
 
 ```
 
 
