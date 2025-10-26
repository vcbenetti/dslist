🎮 DSList - API de Listagem de Jogos
📄 Descrição do Projeto
O DSList é o projeto de Backend (API RESTful) desenvolvido durante o Intensivão Java Spring da DevSuperior. O objetivo principal é fornecer uma API robusta e eficiente para gerenciar listas de jogos eletrônicos, permitindo que os usuários organizem seus títulos favoritos em coleções personalizadas e controlem a ordem de exibição.

Este repositório contém a lógica de negócios, o acesso a dados e os endpoints necessários para suportar um frontend de catálogo de jogos.

✨ Funcionalidades (Endpoints da API)
A API oferece os seguintes recursos:

Listagem de Jogos:

Buscar todos os jogos com informações resumidas.

Buscar um jogo específico por ID, exibindo detalhes completos.

Gestão de Listas:

Buscar todas as listas de jogos.

Buscar os jogos pertencentes a uma lista específica (filtrando por listId).

Funcionalidade Especial: Mover um jogo de posição dentro de uma lista, permitindo a personalização da ordem.

Conectividade: Configuração de CORS para permitir o consumo da API por um frontend externo (Ex: React/Next.js).

💻 Tecnologias Utilizadas (Backend)
Linguagem: Java

Framework: Spring Boot

Persistência: Spring Data JPA / Hibernate

Banco de Dados (Desenvolvimento/Teste): H2 Database

Gerenciador de Dependências: Apache Maven

Outros: Queries SQL nativas para otimização de busca e ordenação.
