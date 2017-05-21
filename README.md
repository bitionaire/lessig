<img alt="logo" src="https://cdn.rawgit.com/bitionaire/lessig/master/lessig.svg" width="311" height="64" />

Command-line `.less` to `.css` recursive compiler.

## Usage

Just call the CLI with the source directory of your less files. All `.less`
within this directory and all subdirectories will be compiled to `.css` files.

```bash
lessig ./src
```

With the `-w` or `--watch` option a watcher task will be started.

```bash
lessig ./src --watch
```