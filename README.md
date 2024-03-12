
⚠️ This is a pr-maintained fork from the [original repo](https://github.com/jmoiron/sqlx) to keep some maintanance

# go/sqlx

[![Code-Testing](https://github.com/go-sqlx/sqlx/actions/workflows/test.yaml/badge.svg)](https://github.com/go-sqlx/sqlx/actions/workflows/test.yaml)

Quick dating the lib:

- **🧐 What is sqlx?**  
   sqlx is a library which provides a set of extensions on go's standard
  `database/sql` library.
- **🚀 Why use sqlx?**  
   Marshal rows into Structs, Named Prepared Statements, `Get` and `Select` to go quickly from query to struct/slice
- **🤝🏻 comapitble with the native packages?**  
   sqlx leaves the underlying interfaces untouched and just superset on the standard ones

## install

### Latest and Greatest

```
    go get github.com/go-sqlx/sqlx
```

### Older Versions from jmoiron

Jmoirons version 1.3.5 is equal with our version 1.3.6 
> ⚠️ not the newest version, but from there you can migrate up  
> (old releases won't work of this repo and or just here for documentation purposes)

```diff
    module ...

    go 1.20

+   replace github.com/jmoiron/sqlx v1.3.5 => github.com/go-sqlx/sqlx v1.3.6

    require(
        ...
    )
```
