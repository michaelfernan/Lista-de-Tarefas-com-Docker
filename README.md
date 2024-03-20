# Projeto Todo App com Docker

## Descrição
Este projeto, realizado como uma avaliação da Trybe no curso de Desenvolvimento Web, envolve a utilização de Docker para construir e gerenciar containers para um aplicativo de tarefas (todo app). O objetivo é demonstrar proficiência no uso de Docker, gerenciando imagens e containers de forma eficaz.

## Requisitos do Projeto
O projeto consiste em várias tarefas relacionadas ao Docker, incluindo a criação de containers, manipulação de imagens e configuração de Dockerfiles para diferentes partes de um aplicativo todo.

### Comandos Docker

1. **Criação de Container (01container):** Usar a imagem Alpine 3.12 para criar um container nomeado `01container`.
2. **Inicialização do Container:** Iniciar o container `01container`.
3. **Listagem de Containers:** Listar containers filtrando pelo nome `01container`.
4. **Execução de Comando em Container:** Executar `cat /etc/os-release` no `01container`.
5. **Remoção de Container:** Remover o container `01container`.
6. **Download de Imagem do Nginx:** Baixar a imagem `nginx 1.21.3-alpine`.
7. **Criação e Execução de Container Nginx:** Rodar um container com a imagem do nginx mapeando a porta 3000.
8. **Parada de Container:** Parar o container `02images`.

### Dockerfile

9. **Build do Dockerfile do Back-End:** Criar uma imagem `todobackend` a partir do Dockerfile do back-end.
10. **Build do Dockerfile do Front-End:** Criar uma imagem `todofrontend` a partir do Dockerfile do front-end.
11. **Build do Dockerfile de Testes:** Criar uma imagem `todotests` a partir do Dockerfile de testes.

## Tecnologias Utilizadas
- Docker
- Node.js (para o aplicativo todo)
- Nginx

## Objetivos de Aprendizado
- Prática com Docker, incluindo gerenciamento de imagens e containers.
- Configuração de ambientes isolados para desenvolvimento, teste e produção.
- Compreensão da importância da virtualização e contêinerização no desenvolvimento de software.

## Contribuições
Este projeto é uma avaliação individual, destinada a demonstrar habilidades individuais no uso de Docker. Portanto, contribuições diretas de terceiros não são aplicáveis.

## Notas Adicionais
- A atenção aos detalhes dos requisitos e a adesão às boas práticas são cruciais.
- Este projeto é uma parte importante do processo de avaliação e crescimento no curso de Desenvolvimento Web da Trybe.

---

⚠️ **Lembrete:** É essencial manter a conformidade com as diretrizes do Linter e as melhores práticas de codificação e uso do Docker.
