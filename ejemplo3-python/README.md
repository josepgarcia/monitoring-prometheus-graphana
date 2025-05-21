
# Verificar funcionamiento
docker compose up -d

curl http://localhost:8000

Podemos ver si la app està enlazada desde
http://localhost:9090/targets

# Metrics
docker compose up -d --build app

