
# testIT

Web сервис для проведения онлайн тестирования студентов технических вузов.

Стэк технологий:
- backend: Django, DRF
- frontend: JavaScript, Vue


## Документации

- [Пользователя](./docs/docs-user/Docs.md)
- [Backend-разработчика](./docs/docs-backend/Docs.md)
- [Frontend-разработчика](./docs/docs-frontend/Docs.md)


## Run

```bash
git clone https://github.com/Brajenko/testIT_fullstack
cat > .env << EOL
POSTGRES_NAME='<название бд>'
POSTGRES_USER='<имя пользователя бд>'
POSTGRES_PASSWORD='<пароль пользователя бд>'
EOL
docker compose up
```

