# gh-graphql-examples

I use [GitHub CLI](https://github.com/cli/cli).

### [Me](./examples/queries/Me.graphql)

```sh
gh api graphql -f query="$(cat ./examples/queries/Me.graphql)"
```

### [UserRepositories](./examples/queries/UserRepositories.graphql)

```sh
gh api graphql -F user='***' -f query="$(cat ./examples/queries/UserRepositories.graphql)"
```

### [CreateIssue](./examples/mutations/CreateIssue.graphql)

```sh
gh api graphql -F repositoryId='***' -F title='***' -f query="$(cat ./examples/mutations/CreateIssue.graphql)"
```
