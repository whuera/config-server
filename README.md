# config-server
config-server for microservices

configurations for MySql

 #Application Configuration
  server:
    port: 8091

  # ===============================
  # DB
  # ===============================
  spring:
  datasource:
    url: jdbc:mysql://localhost:3306/dbemails?serverTimezone=UTC
    driverClassName: com.mysql.cj.jdbc.Driver
    username: whuera
    password: "*Weho7755*"

  # ===============================
  # JPA / HIBERNATE
  # ===============================
  jpa:
      hibernate:
        ddl-auto: update
      properties:
        hibernate:
          show_sql: true
          use_sql_comments: false
          format_sql: false



