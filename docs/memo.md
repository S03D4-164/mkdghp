# Memo

## GitHub Actions

### python

cache: 'pip' requires requirements.txt

```
Error: No file in /home/runner/work/mkdghp/mkdghp matched to [**/requirements.txt or **/pyproject.toml], make sure you have checked out the target repository
```

### mkdocs

Github actions require write permission:

```
INFO    -  Copying '/home/runner/work/mkdghp/mkdghp/site' to 'gh-pages' branch and pushing to GitHub.
remote: Write access to repository not granted.
fatal: unable to access 'https://github.com/S03D4-164/mkdghp/': The requested URL returned error: 403
```

Settings > Actions > General > Workflow permissions > Read and write permissions 
