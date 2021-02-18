## Description

This repository is to demonstrate a behavior of `nodemon` in which it does not listen to files in relative path.

## Steps to reproduce

1. Execute `cd nodemon-dir` in the repo.
2. Execute `npm run subdir-test`.
3. Open another terminal.
4. Inside the new terminal, go to the repo.
5. Execute `touch tmp-dir/foo`.
6. Check `nodemon` is not triggered.
