# raft
This is a repository to help me learn / practice programing languages via the "learn-by-doing" method. This
repository implements the [Raft Consensus Algorithm](https://raft.github.io/) in various programing
languages and with whatever design best fit for each language. I chose to implement this per language
as it will exercise
- Command Line Interface
- Network IO
- JSON Parsing
- Complex State Machines
- Callbacks / Timeouts

This was inspired from my Networks and Distributed Systems class [cs3700](https://cbw.sh/3700/index.html).
Specifically [project6](https://cbw.sh/3700/raft.html)

## Directory Structure
Each programing language has its own directory containing the implementation
```
raft/
    python/
    racket/
    go/
    haskell/
    configs/
        simple-1.json
        simple-2.json
    run.py
    test.py
```

It is the responsibility of whatever build tools are used within each language to call `run.py` and `test.py`
properly to test the implementation.

## Installation
To run the simulations you'll need
- A python2 interpreter
- An OS that supports Unix Domain Sockets
