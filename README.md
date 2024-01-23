# Full Cycle 3.0 > Integração Contínua > Desafios > Pipeline de CI com SonarCloud

## Instruções

```bash
cd root-folder-of-repo/

# Construir ambiente Docker
docker-compose up --build -d

# Acessar rota inicial
curl http://localhost:3000

# Executar testes
docker-compose exec app npm test
```
