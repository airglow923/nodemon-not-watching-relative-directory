## Update

`nodemon` by default watches files with extensions `js,mjs,json`.

Change this to `*` and `nodemon` will listen to all the files in a directory.

## Description

This repository is to demonstrate a behavior of `nodemon` in which it does not listen to files in relative path.

## Steps to reproduce

1. Clone this repository.
2. `cd` to cloned repository.
3. Execute `cd nodemon-dir`.
4. Execute `npm run relative-dir-test`.
5. Open another terminal.
6. `cd` to cloned repository.
7. Execute `touch tmp-dir/foo`.
8. Check `nodemon` is not triggered.
