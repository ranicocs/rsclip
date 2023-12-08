# rclip
CLI utility to copy the contents of a file to the clipboard written in Rust.
Inspired in xclip. Supports X11.

## Installation

### Cargo
```bash
cargo install rclip
```

## Usage

### Paste
Paste the contents of a file to the clipboard.

```bash
$ rclip
Clipboard contents
$ rclip -p
Clipboard contents
$ rclip --paste
Clipboard contents
```

### Copy
Copy the contents of a file to the clipboard.

```bash
$ rclip <file>
$ rclip -c <file>
$ rclip --copy <file>
```

