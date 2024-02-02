# sonarqube-dockerization

- Stand up Postgresql on port 5432 as database.
- Up sonarqube server on 9000 port

**note:** Replace ports and versions into yml file. For example, with a .env file and using patterns. Read more about docker-compose files.

To stand up container, execute following on terminal:
```bash
  docker compose up -d
```
**note:** Tested on Windows 11 Pro 22 H2 and Docker desktop  4.21.1 (114176).
