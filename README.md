# Notedux CLI

A command-line tool that turns terminal output into editable notes with Notedux (https://notedux.com).

Pipe command output directly to Notedux, create notes from scripts, or manage your notes from the terminal. No login required.

## Features

- **Terminal pipelines** – Pipe output from any command directly into Notedux.
- **Script integration** – Generate and update notes automatically from shell scripts.
- **Create notes** – Create notes directly from your terminal.
- **Read and update notes** – View and modify existing notes.
- **No login required** – No accounts, passwords, or registration.
- **Cross-platform** – Works on macOS and Linux.

## Turn terminal output into formatted notes

Notedux CLI supports Unix pipelines, allowing you to send the output of virtually any command directly to Notedux.

For example, generate a server report and turn it into a shareable online note:

```bash
hostnamectl | notedux add
```

Or capture running Docker containers:

```bash
docker ps -a | notedux add
```

You can also pipe output from scripts, system commands, or other tools:

```bash
df -h | notedux add
```

Notedux creates or updates your note and returns a unique URL. Open that link in your browser to edit, format, organize, or export the content as a PDF.

**Your terminal output becomes a shareable document in seconds.**

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