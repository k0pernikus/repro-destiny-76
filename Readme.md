# Example for issue 76

This is a example repo for [desiny's issue 76][https://github.com/benawad/destiny/issues/76].

```
git clone git@github.com:k0pernikus/repro-destiny-76.git
npm ci && npx tsc
```

The error happens when you run:

```
destiny "src/**/*.*"

INFO: Resolving files.
INFO: Generating tree for: src/**/*.*
ERROR: Cannot find import ../../../package.json
If you think this is a bug, you can report it: https://github.com/benawad/destiny/issues
```
