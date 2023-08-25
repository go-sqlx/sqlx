# This is a fork from the [original repo](https://github.com/jmoiron/sqlx) to keep some maintanance

Hi there,

I am a bit sad that the original developer abandoned the project and does not merge any more fixes and stuff, so I try to bring it to at least some life again. I would love to get some support doing that, so if you're interested in becoming a maintainer, feel free to contact me [@uvulpos](https://github.com/uvulpos)

---

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

We support older versions from v1.2.0 to 1.3.5

```diff
    module ...

    go 1.20

    + replace github.com/jmoiron/sqlx v1.3.5 => github.com/go-sqlx/sqlx v1.3.5
    + replace github.com/jmoiron/sqlx v1.3.4 => github.com/go-sqlx/sqlx v1.3.4
    + replace github.com/jmoiron/sqlx v1.3.3 => github.com/go-sqlx/sqlx v1.3.3
    + replace github.com/jmoiron/sqlx v1.3.2 => github.com/go-sqlx/sqlx v1.3.2
    + replace github.com/jmoiron/sqlx v1.3.1 => github.com/go-sqlx/sqlx v1.3.1
    + replace github.com/jmoiron/sqlx v1.3.0 => github.com/go-sqlx/sqlx v1.3.0
    + replace github.com/jmoiron/sqlx v1.2.0 => github.com/go-sqlx/sqlx v1.2.0

    require(
        ...
    )
```
