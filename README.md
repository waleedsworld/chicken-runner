# Chicken-Runner (archived fork)

> **Archival note:** This is a preserved fork of a third-party open-source project. It was
> **not written by the owner of this account.** The original game — code and art — is the
> work of **Andrew Aodh Zhao** (GitHub [`0xFFFFF`](https://github.com/0xFFFFF)), forked from
> `azmoaum/chicken-runner`. See [`NOTICE.md`](./NOTICE.md) for full attribution. The original
> commit history (2013–2015) is kept intact and unaltered.

## About the original project

Chicken-Runner is an **endless-runner game written in Java** under the MVC architecture.

Endless-runner games are platform games in which the player character moves continuously
forward through a procedurally generated, theoretically endless world. Controls are limited
to jumping, attacking, or special actions, and the goal is to get as far as possible before
the character dies.

## How to play

- **Arrow keys** — move and jump.
- **Space bar** — shoot bullets at enemies.
- Collect **apples** for points.

## Building (original Java sources)

The sources under `src/` are plain Java (Swing). To compile and run locally:

```bash
mkdir -p out
javac -d out src/*.java
java -cp out:. ChickenRunnerController
```

> The game loads sprites from the `images/` directory using relative paths, so run it from
> the repository root. A JDK (8 or newer) is required.

## Status

Archived, unmodified, and preserved with attribution. Not maintained. Not deployed.
