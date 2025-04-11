- to remove branches locally

```ssh
git branch -d test
git branch -d dev
```

- to remove branches remotly

```ssh
git push origin --delete test
git push origin --delete dev
```

### the annotated tag

is a full object in the repo and hase it's sha hash it can store message and appear in the github

### the lightwieght tag

is a pointer to a commit, can not store meta data and does not appear in the github

### list tages

```ssh
git tag
```

### remove tages local and remotly

```ssh
git tag -d V1.0
git push origin --delete tag V1.0
```
