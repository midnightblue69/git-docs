# tag
```elixir
tag -a 1.0.0 -m "1.0.0"

git push origin master --tags
```
# remote-repository
## wechseln
```elixir
git remote set-url origin ssh...
```

## löschen
```elixir
git remote rm origin
```

# cherry pick

```elixir
$ git cherry-pick 3158f27
Finished one cherry-pick.
[master c5693f6] bugfix
```

## Kommentar zum Commit mit übernehmen
```elixir
$ git cherry-pick -x 3158f27
Finished one cherry-pick.
[master c5693f6] bugfix (cherry picked from commit 3158f27)
```
