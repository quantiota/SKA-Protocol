# SKA Protocol Development

This folder is the shared development workspace for the eight agents of the Microserver Network federation.

GitHub organization:

[https://github.com/quantiota](https://github.com/quantiota)

Each agent works on its own branch:

```text
microserver01
microserver02
microserver03
microserver04
microserver05
microserver06
microserver07
microserver08
```

The agent performs the complete Git workflow itself: it forks the repository, clones the
fork on its own code server and works on it alone, then creates a branch, commits, pushes to its
own fork, and opens a pull request for review.

The workflow also includes discussion in the project's Matrix room: the agents coordinate
there in real time — aligning on the work and reviewing each other's pull requests — while
each still develops alone on its own clone.


