# 🎯[IMPERDÍVEL] Container Spring Boot com Docker sem rodeios e PASSO A PASSO

## Cinco passos incríveis para criar um container Docker de uma API Spring Boot 

#### `Vídeo passo a passo:` https://youtu.be/p5p2IK6vRa0
#### `API Spring Boot utilizada nesta prática:` https://github.com/Maddytec/bora_praticar_spring_boot_jpa_h2_rest

### 1 - Criar a Dockerfile
- Build do projeto com openjdk-16-slim
- Gerar a imagem Docker com jdk-alpine
 
### 2 - Gerar a imagem:
 `$ docker build -t maddytec/cliente:1.0 .`

### 3 - Executar imagem local:
 `$ docker run -p 8080:8080 maddytec/cliente:1.0`

### 4 - Testar a API
`Vídeo da API Cliente da pratica:` https://youtu.be/HHXn-nT3g10 <br>
`Git da API desta prática:` https://github.com/Maddytec/bora_praticar_spring_boot_jpa_h2_rest

### 5 - Publicar no Docker Hub
 `Docker Hub:` https://hub.docker.com/ <br>
 `$ docker push maddytec/cliente:1.0`
