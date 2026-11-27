# SoporteYa · Mesa de ayuda de TI
 
Proyecto guía del programa ADSO (SENA, ficha 3230489). Los funcionarios de una empresa reportan
fallas de tecnología y los técnicos las atienden con tiempos de respuesta medidos.
 
## Cómo ejecutarlo
 
```bash
sudo -u postgres psql -c "CREATE DATABASE soporteya OWNER adso;"
DB_PASSWORD=adso2026 ./mvnw spring-boot:run
```
 
Abra http://localhost:8080
 
## Autor
 
| Aprendiz | Usuario de GitHub | Ficha |
|---|---|---|
| Erick Jr Cantillo | Erickxz6 | 3230489 |