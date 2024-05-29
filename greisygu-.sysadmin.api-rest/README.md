# GREISYGU - BACKEND API REST

# Tecnologias utilizadas

* Openjdk
* Spring Boot
  * Spring Web 
  * Lombok
  * Spring Boot Data JPA
  * H2 Database
  * Junit
  * Mockito
  * Swagger UI
* Postgre SQL
* Docker Engine



# ¿Como correr el proyecto?
Debe clonar el repositorio de la aplicacion que se encuentra en la plataforma de Github:
```
$ git clone https://github.com/tupAlexLopez/greisygu-.sysadmin.api-rest.git
```


## Hay varias formas de correr el proyecto.
1. Dirigase al directorio donde se encuentra el repositorio clonado.
    * Se recomienda que lo haga a traves de la consola de su sistema (CMD, bash o el que usted utilice)
    * Tambien puede hacer uso de IDEs(IntelliJ CE, Eclipse, STS, etc) o incluso editores de texto (VS Code)
      * **Si lo hace de esta manera, tenga en claro que se utilizara la consola de comandos para correr el proyecto.** 


## Usted puede correr el proyecto a traves de:
### Maven
Si opta por esta opcion, en **sistemas Linux debe conceder permisos al archivo mvnw** para que este
pueda ejecutar el proyecto correctamente.
##### Windows:
```
$ ./mvnw spring-boot:run
```
##### Linux:
```
$ chmod +x mvnw
$ ./mvnw spring-boot:run 
```

### Docker
``` 
$ docker build -t springboot-app .
$ docker run -d -p 8080:8080 --name springboot-api-rest-app springboot-app    
```

### Luego de ejecutar los comandos haga click en el siguiente enlace:  http://localhost:8080

### Puede visualizar el proyecto en produccion desde el siguiente enlace: https://greisygu-backend-api-rest.onrender.com

#### Importante
 Al dirigirse al enlace se mostrara la documentacion oficial de la API REST mediante [Swagger UI]( https://swagger.io/tools/swagger-ui/ ) donde podemos probar los endpoints sin necesidad de tener que instalar programas de terceros en nuestra maquina como **Postman**, **Insomnia** u otro cliente. 