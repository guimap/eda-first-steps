# eda-first-steps

Este repositório contém um projeto de exemplo Spring Boot localizado na pasta `app`. O projeto expõe um endpoint simples e inclui a configuração necessária para build e execução via Docker Compose.

## Estrutura
- `app/`: código-fonte do projeto Spring Boot e Dockerfile para build da imagem.
- `docker-compose.yml`: orquestra a criação da imagem e expõe a aplicação na porta 8080.

## Executando com Docker Compose
1. Construa e suba os serviços:
   ```bash
   docker-compose up --build
   ```
2. Acesse `http://localhost:8080` para ver a resposta padrão do endpoint raiz.
