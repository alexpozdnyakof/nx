# format:write

Overwrite un-formatted files

## Usage

```bash
format:write
```

### Options

| Option            | Description                                        | Default value |
| ----------------- | -------------------------------------------------- | ------------- |
| `--help`          | Show help                                          |               |
| `--version`       | Show version number                                |               |
| `--quiet`         |                                                    |               |
| `--parallel`      | Parallelize the command                            | `false`       |
| `--maxParallel`   | Max number of parallel processes                   | `3`           |
| `--files`         | A list of files delimited by commas                |               |
| `--uncommitted`   | Uncommitted changes                                |               |
| `--untracked`     | Untracked changes                                  |               |
| `--all`           | All projects                                       |               |
| `--base`          | Base of the current branch (usually master)        |               |
| `--head`          | Latest commit of the current branch (usually HEAD) |               |
| `--exclude`       | Exclude certain projects from being processed      | ``            |
| `--only-failed`   | Isolate projects which previously failed           | `false`       |
| `--file`          | output file (e.g. --file=.vis/output.json)         |               |
| `--apps-and-libs` |                                                    |               |
