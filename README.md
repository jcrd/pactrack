# pactrack
pactrack tracks remote pacman packages and reports their update status.

## Usage
```
usage: pactrack [command]

commands:
  add       PKG...   Track packages
  remove|rm PKG...   Untrack packages
  update    [-a]     Track latest version of updated packages
                      -a: all
  prune     [-a|-i]  Untrack packages with installed updates
                      -a: untrack all
                      -u: untrack all updated
  status    [-u]     Show status of tracked packages
                      -u: show only updated
```

## License
This project is licensed under the MIT License (see [LICENSE](LICENSE)).
