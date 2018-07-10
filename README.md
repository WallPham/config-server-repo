# README #
All configurable parameters of microservices.
Configure <spring.profiles.active> in `bootstrap.yml` file of client with below value

######## DEVELOPMENT PROFILE ######## 
spring:
  profiles: 
    active: development
management:
  security:
    enabled: false

######## PRODUCTION PROFILE ######## 
spring:
  profiles: 
    active: production
management:
  security:
    enabled: true
