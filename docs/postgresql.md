# PostgreSQL

## O que é
PostgreSQL é um sistema de gerenciamento de banco de dados relacional, open-source, com recursos avançados (ACID, índices, tipos, extensões).

## Por que aprender
- Robustez e performance
- Muito usado em produção
- Suporte a features avançadas (JSON, índices GIN, procedures)

## O que estudar aqui
- Instalação e configuração básica
- SQL: SELECT, INSERT, UPDATE, DELETE, JOINs
- Modelagem: normalização, chaves primárias/estrangeiras
- Índices, EXPLAIN, otimização básica
- Backups e restore (pg_dump / pg_restore)
- Integração com linguagens (Java, Node.js)

## Projetos sugeridos
- CRUD de uma entidade (ex: tarefas) com persistência em PostgreSQL
- Normalizar um modelo simples e criar migrations
- Consultas com joins e índices para performance

## Recursos / Materiais
- Exemplo de schema e migrations
- Comandos comuns (psql snippets)
- Dicas para tuning básico

## Exercícios rápidos
1. Criar tabela `usuarios` com PK e inserir dados.
2. Fazer consulta com JOIN entre `usuarios` e `pedidos`.

---
