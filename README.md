# worf-packages

Package build definitions (melange) built by WORF. WORF only reads this repo; changes come in by commit / PR.

```
defaults.yaml                 repo-wide defaults
pipelines/                    optional shared melange pipelines
packages/<name>/
  package.melange.yaml        melange spec (no environment keyring/repositories)
  worf.yaml                   metadata, update policy
  patches/, files/            optional
```

Annotated examples and the rules:
[worf/examples/package-repo](http://10.0.10.5:30008/jcooper/worf/src/branch/main/examples/package-repo)
