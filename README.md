
# Rustic Notes

**Rustic Notes** is your no-frills, terminal-first note-taking companion. Whether you're jotting down quick ideas or organizing your thoughts with tags, Rustic Notes keeps things lightweight, fast, and flexible—just the way you like it. With both a CLI and TUI interface, it's designed for efficiency without sacrificing the simplicity that makes it a joy to use.

Inspired by the Unix philosophy and the suckless mindset, Rustic Notes gets out of the way so you can focus on what matters: your notes.

## Features
- **CLI** and **TUI** interfaces for all note-taking preferences.
- **Tags** for easy organization.
- **Vim-style navigation** in the TUI—because why change a good thing?
- Powerful **search** by tags or full content.
- Add, read, and delete notes in seconds.
- **Confirmation prompts** for safe deletions.
- Built-in **help feature** to keep you on track.
- **No external dependencies**—just raw, efficient code.

## Installation

1. Clone the repository and get set up:
   ```bash
   git clone https://github.com/your-username/rustic-notes.git
   cd rustic-notes
   ```

2. Make sure you’ve got Python 3 installed.

3. If needed, make the programs executable:
   ```bash
   chmod +x rustic-notes rustic-notes-tui
   ```

4. For convenience, add the programs to your `$PATH`:
   ```bash
   sudo mv rustic-notes /usr/local/bin
   sudo mv rustic-notes-tui /usr/local/bin
   ```

And that's it. Now you can run `rustic-notes` and `rustic-notes-tui` just like any other command.

---

## Usage

### CLI Usage

The CLI is all about quick efficiency. Just type `rustic-notes` followed by a command, and you're good to go:

```bash
rustic-notes [command] [arguments]
```

#### CLI Commands

- **add**: Create a new note.
  ```bash
  rustic-notes add
  ```
- **view**: View all your notes.
  ```bash
  rustic-notes view
  ```
- **read [id]**: Read a note by ID.
  ```bash
  rustic-notes read 1
  ```
- **delete [id]**: Delete a note by ID (with no takebacks).
  ```bash
  rustic-notes delete 1
  ```
- **search [keyword]**: Search for notes by keyword (tags by default, use `--full` to search content).
  ```bash
  rustic-notes search "keyword"
  ```

### TUI Usage

For a more immersive experience, the **TUI** interface is here for you. Fire it up with:

```bash
rustic-notes-tui
```

### TUI Keybindings

- **`k`**: Move up.
- **`j`**: Move down.
- **Enter**: Read the selected note.
- **`d`**: Delete the selected note (confirmation required).
- **`/`**: Search notes by keyword.
- **`a`**: Add a new note.
- **`q`**: Quit when you're done.
- **`?`**: Help (because nobody remembers all the keybindings forever).

---

## Where Your Notes Live

Notes are saved as plain text files in `~/rustic-notes/notes/`. Each note has a timestamp, tags, and your content, so you can always peek at them outside of the app if you like—but Rustic Notes has you covered for all the management you'll need.

---

## Contributing

Got a feature idea or a tweak to make Rustic Notes even smoother? Contributions are welcome! Just remember, we’re keeping things light and lean:
- Fork the repository.
- Submit issues or pull requests.
- Keep it minimal—this tool thrives on simplicity.

---

## License

Rustic Notes is licensed under the **GPLv3**. Feel free to use, share, and modify it—but let’s keep it open for everyone to enjoy.

---

### Final Thoughts

Rustic Notes was built to make note-taking a breeze in the terminal, whether you’re jotting down thoughts or organizing your ideas with tags. With no dependencies and intuitive keybindings, it’s here to help you focus on what matters: your notes.
