# Apps2Samsung example repository

A working **independent repository**, built from the
[template in tizen-community-packages](https://github.com/Apps2Samsung/tizen-community-packages/tree/main/templates/independent-repo).
Look here to see what a finished setup looks like: [`repository.input.json`](repository.input.json),
the [publish workflow](.github/workflows/publish-repository.yml) and its
[runs](https://github.com/Apps2Samsung/repository-example/actions). The format is in
[docs/repositories.md](https://github.com/Apps2Samsung/tizen-community-packages/blob/main/docs/repositories.md).

It lists two Apps2Samsung apps, Reolink Viewer and Overscan, which are also in the official catalog.
There's no need to add it for everyday use; you can, to try how a repository looks in Apps2Samsung
("Also offered by", the key check, Send sources to TV).

Repository URL:

```
https://apps2samsung.github.io/repository-example/repository.json.signed
```

Key fingerprint (compare it with what Apps2Samsung shows):

```
f4085b51158ba86be21552c39a720ae0cf27c670989b930c02a7896784eb589c
```

The repository id is `io.github.apps2samsung.pilot`: it started as the pilot for end-to-end testing,
and an id can never change.
