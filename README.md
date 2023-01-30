# gh-graphql-examples

https://github.com/cli/cli

### [Me](./examples/queries/Me.graphql)
```sh
gh api graphql -f query="$(cat ./examples/queries/Me.graphql)"
```

### [UserRepositoryNames](./examples/queries/UserRepositoryNames.graphql)
```sh
gh api graphql -F user="tmtmtoo" -f query="$(cat ./examples/queries/UserRepositoryNames.graphql)"
```
