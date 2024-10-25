# Desafio de Projeto: Executando uma Aplicação HTML em um Container Apache utilizando Docker-Compose

## Descrição
Desenvolvido com base no desafio proposto, utilizei do Docker Compose para configurar e executar uma aplicação HTML simples em um servidor Apache. O objetivo é colocar em prática o uso de containers para servir conteúdo web.

## Passo a Passo realizado

1. **Criação do arquivo `docker-compose.yml`**:
   - Especificar as definições para o serviço Apache (httpd) no arquivo YAML.
   - Indicar o diretório onde os arquivos HTML, CSS e JS estarão localizados.
  
2. **Implementação da Aplicação Web**:
   - Desenvolvimento de uma página HTML simples e pouco personalizada.
  
3. **Subir o Projeto para o GitHub**:
   - Enviar o arquivo `docker-compose.yml` e os arquivos HTML/CSS/JS para um repositório no GitHub.
   - Documentar o projeto com instruções de uso e objetivos, visando enriquecer o portfólio.

## Pré-requisitos

- Conhecimento básico em Docker e Docker Compose.
- Conceitos básicos de Apache HTTP Server.
- Noções de HTML, CSS e, opcionalmente, JavaScript.
- Computador com sistema operacional à sua escolha (Windows, Linux, ou MacOS).

## Como Executar

1. **Faça o clone deste repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
2. **Execute o Docker Compose**:  
   ```bash
   docker-compose up -d
3. **Acesse o site**:
- Abra o navegador e acesse http://localhost:80 para visualizar sua aplicação em execução.
