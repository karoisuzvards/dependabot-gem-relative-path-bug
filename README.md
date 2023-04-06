# dependabot-gem-relative-path-bug
Demonstrate a bug of Dependabot Ruby having gems referenced by path using relative paths

Repo has following structure (reduced sample from monorepo):

```
ruby
  |_apps
    |_hello_valdis
  |_gems
    |_hola
```

`hello_valdis` - sample app that uses gem from relative directory
`hola` - gem that is being used by `hello_valdis` app

