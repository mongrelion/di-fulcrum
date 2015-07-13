# Fulcrum
---

[Fulcrum](https://github.com/fulcrum-agile/fulcrum) Docker image


This version runs with [SQLite3](https://sqlite.org/).  
I suggest creating a shared volume so not to lose the database when the process gets restarted.

`docker run -p 3000:3000 -v ~/fulcrum/production.sqlite3:/usr/src/app/db/production.sqlite3`
