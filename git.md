# Branch
## Delete branch

```
$ git push --delete origin branch_name   # to delete branch on remote
```


# Tag
## Create a tag

```
$ git tag -a v1.4 -m 'my version 1.4'
$ git tag -a v1.4 7c5f24d  # Tag with a specific commit
```

## Push a tag to remote

```
$ git push origin v1.4
```

## Delete a tag

```
$ git push --delete origin tagname 
```
