Clone and run `go generate` and you should see

```sh
...../schema.graphql:13: conflicting definition for FooBarA; this can indicate either a genqlient internal error, a conflict between user-specified type-names, or some very tricksy GraphQL field/type names: expected 2 fields, got 1
exit status 1
main.go:9: running "go": exit status 1
```
