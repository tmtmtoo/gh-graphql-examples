# gh-graphql-examples

I use [GitHub CLI](https://github.com/cli/cli).

### [Me](./examples/queries/Me.graphql)

```sh
gh api graphql -f query="$(cat ./examples/queries/Me.graphql)"
```

### [UserRepositories](./examples/queries/UserRepositories.graphql)

```sh
gh api graphql -F user="tmtmtoo" -f query="$(cat ./examples/queries/UserRepositories.graphql)"
```
