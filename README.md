# Udemy ROR Free Course- Contact List.

- `psql` Accessing postgres console.
- `\l`   Listing databases

## installing project on new machine, can give several erros: 

- 2.3.7 ruby need specific bundle version, if installed inside other ruby projects. Bundle is in the project context.
https://makandracards.com/makandra/9741-run-specific-version-of-bundler

- psql: FATAL: database “<user>” does not exist. 
Run `createdb` to solve this.
https://stackoverflow.com/questions/17633422/psql-fatal-database-user-does-not-exist

- “database does not exist” error with postgresql
Run `bin/rake db:create` to solve this.
https://stackoverflow.com/questions/25611004/rake-dbcreate-throws-database-does-not-exist-error-with-postgresql

Commands list: https://chartio.com/resources/tutorials/how-to-list-databases-and-tables-in-postgresql-using-psql/

Project's GIST - https://gist.github.com/brunojppb/338e08da867f4cb05a8de9d9523f0ffd 