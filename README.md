# debug

Simple github action to debug our workflow

## Usage

```
on:
  push:

jobs:
  test:
    runs-on: ubuntu-latest
    name: just test debug action
    steps:
      - uses: o-devops/debug@main
```
