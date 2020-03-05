# Git commands

+ Create and checkout branch: 

```bash
$ git checkout -b branch_name
```

+ Push branch to remote and track: 

```bash
$ git push -u origin branch_name
```

+ checkout remote branch: 

```bash
$ git checkout -b branch_name origin/branch_name
```

+ Change name (file or folder, for a folder the full route from where you are): 

```bash
$ git mv old_filename new_filename
```

+ Create annotated tag: 

```bash
$ git tag -a <tagname> -m '<message>'
```

+ View tags: 

```bash
$ git tag
```

+ View tags with annotations: 

```bash
$ git tag -n
```

+ View specific tag with annotation: 

```bash
$ git tag -n <tagname>
```
