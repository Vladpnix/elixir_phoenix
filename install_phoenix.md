Install phoenix

```
mix local.hex
mix archive.install hex phx_new
```
```
mix help phx.new
mix phx.new test --database sqlite3
```
```
postgres - via https://github.com/elixir-ecto/postgrex
mysql - via https://github.com/elixir-ecto/myxql
mssql - via https://github.com/livehelpnow/tds
sqlite3 - via https://github.com/elixir-sqlite/ecto_sqlite3
```
In order to talk to databases, Phoenix applications use another Elixir package, called Ecto.
If you don't plan to use databases in your application, you can pass the --no-ecto flag.
