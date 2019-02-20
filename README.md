# Typical Go Server (WIP)

This project aim to provide starter/example project for API Service in Go.

- [x] [KISS](https://en.wikipedia.org/wiki/KISS_principle) and Go Idiomatic
- [x] [Rails-like](https://guides.rubyonrails.org/getting_started.html#creating-the-blog-application) Project Layout
  - [x] [Separation of concerns](https://en.wikipedia.org/wiki/Separation_of_concerns)
  - [x] [Dependency Injection](https://stackoverflow.com/questions/130794/what-is-dependency-injection)
- [x] [12 Factor App](https://12factor.net/) and micro-services friendly
  - [x] Using environment variable as config (for development, use [direnv](https://direnv.net/))
  - [x] Package Management/Vendoring
  - [x] [Graceful Shutdown](https://12factor.net/disposability)
  - [x] Database Administration (Create/Drop/Migrate/Rollback)
  - [ ] [Health Check](https://microservices.io/patterns/observability/health-check-api.html)
  - [ ] Travis CI example
  - [ ] Docker example
- [ ] [Self Testing Code](https://martinfowler.com/bliki/SelfTestingCode.html)
  - [x] Generate Mocking class
- [x] Postgres Database
  - [x] Data Access Layer/Repository Pattern
- [ ] Self-explanatory Project
  - [x] [Project README](Project_README.md)
  - [x] Makefile
  - [x] Automatic generate cli/command documentation
  - [x] Automatic generate config documentation
  - [ ] Automatic generate API Doc
- [ ] Misc
  - [ ] Machine Profiling
  - [ ] API Versioning
  - [ ] Cache
  - [ ] Worker

### How to Use

_Under Construction_
<!-- FIXME: -->

### Library Overview
- [urfave/cli](https://github.com/urfave/cli): A simple, fast, and fun package for building command line apps in Go
- [labstack/echo](https://github.com/labstack/echo): High performance, minimalist Go web framework
- [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig): Managing configuration data from environment variables
- [stretchr/testify](https://github.com/stretchr/testify): A toolkit with common assertions and mocks that plays nicely with the standard library
- [uber-go/dig](https://github.com/uber-go/dig): A reflection based dependency injection toolkit for Go.
- [lib/pq](https://github.com/lib/pq): Pure Go Postgres driver for database/sql
- [imantung/go-helper](https://github.com/imantung/go-helper): Helper library collection for golang
- [Masterminds/squirrel](https://github.com/Masterminds/squirrel): Fluent SQL generation for golang
- [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock): Sql mock driver for golang to test database interactions
- [golang/mock](https://github.com/golang/mock): A mocking framework for the Go programming language.
- [olekukonko/tablewriter](https://github.com/olekukonko/tablewriter): ASCII table in golang


### Similar Projects

- [gobuffalo](https://gobuffalo.io/): Web Development eco-system
- [go-swagger](https://goswagger.io/): OpenAPI implementation on Go
- [go-bootstrap](http://go-bootstrap.io/): Generates a lean and mean Go web project.
- [qiangxue/golang-restful-starter-kit](github.com/qiangxue/golang-restful-starter-kit): A RESTful application boilerplate in Go (golang) taking best practices and utilizing best available packages and tools

### Contributing

_Under Construction_
<!-- FIXME: -->


### Authors

* **[imantung](https://github.com/imantung)** - *Initial work* -

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
