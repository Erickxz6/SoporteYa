# SoporteYa

Mesa de ayuda para el soporte técnico interno: tickets por prioridad, categorization por área, tablero para técnicos e indicadores para coordinación.

## Cómo ejecutarlo

### Con Docker (recomendado)

    cp .env.example .env        # y cambie las claves
    docker compose up --build

### En la máquina virtual, sin Docker

    sudo -u postgres psql -c "CREATE DATABASE soporteya OWNER adso;"
    cp .env.example .env        # y cambie las claves
    set -a; source .env; set +a
    ./mvnw spring-boot:run

Abra http://localhost:8080 · usuario de prueba: laura.gomez@soporteya.co · contraseña: Soporte2026
