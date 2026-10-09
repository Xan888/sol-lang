# Sol ☀️

Sol is a Lua-inspired programming language with a standalone macOS interpreter.

## Download

Open this repository’s **Releases** page and download:
`sol-0.6.0-macos-x86_64.zip`

This build targets macOS x86_64. No Python installation is required.

## Getting started

1. Extract the ZIP.
2. Open Terminal in the extracted folder.
3. Run:

```bash
./sol
```

On its first run, Sol installs a user-local copy and configures the terminal command. Open a new terminal afterward to use:

```bash
sol path/to/program.sol
```

Run `sol` without a filename to open the interactive prompt (REPL).

## Try an example

From the extracted folder:

```bash
./sol examples/hello.sol
./sol examples/greet.sol --name "Alex" --age 19
```

## Documentation

Open `documentation.html` from the download for the offline language guide.

## macOS security

This release is not notarized. macOS may require you to allow it through System Settings → Privacy & Security.

## About this repository

This repository distributes Sol releases. The interpreter’s source code is not published here.
