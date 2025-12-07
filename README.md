# Entrega Final - PLN

## Recuperar os dados
```bash
# Juntar as partes
cat volumes.tar.gz.part* > volumes.tar.gz

# Extrair
tar -xzf volumes.tar.gz

# Subir containers
docker-compose up -d
```

## Coleções Qdrant
- vagas_openai (OpenAI embeddings)
- vagas_gemini (Gemini embeddings)

Data de entrega: 08/12/2025
