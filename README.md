# Notedux CLI

A fast command-line client for the Notedux note-taking service.

Create, read, update, delete, and list your notes directly from your terminal.

## Features

- Create notes in seconds
- View note content
- Edit existing notes
- Delete content of notes
- No login required
- Works on macOS and Linux

## Installation

Install globally using npm:

```bash
npm install -g notedux
```

Verify the installation:

```bash
notedux --help
```

## Getting Started

Create your first note:

```bash
notedux generate
notedux add "My first note"
```

The command returns a unique link to your note.


Show a note:

```bash
notedux show
```

Update a note:

```bash
notedux add "Updated text"
```


## Help

Display all available commands:

```bash
notedux --help
```

## Requirements

- Bash
- curl

## License

This project is licensed under the GNU General Public License v3.0.

See the LICENSE file for details.