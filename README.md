# API_SpringBoot_hotel

Este é um aplicativo de reserva de hotel que está conectado a um banco de dados postgresql usando o docker

## Ferramentas
Para funcionar é necessário ter:

- Maven as your build tool

- JDK 1.8+

- Postgresql

<hr>

## Dependencias
Para funcionar é necessário ter:

- Maven as your build tool

- JDK 1.8+

- Postgresql

<hr>

## Instruções sobre como usar

1. Instruções sobre como usar
Baixe o repositório e verifique se o PostgreSQL e o Docker estão instalados em seu sistema.

4. Run the `LearningSpringApplication.java` File in `hotelreservation-springboot/src/main/java/com/learningspring/`

5. Once the application is built and running go in to you web browser and type in `localhost:8080` 

4. Para rodar a aplicação localmente, há a necessidade de passar as inforações da base de dados, conforme exemplo:
```
-DBATES_DB_HOST=jdbc:postgresql://localhost:5432/hotel
-DBATES_DB_USER=postgres
-DBATES_DB_PASSWORD=postgres
```


