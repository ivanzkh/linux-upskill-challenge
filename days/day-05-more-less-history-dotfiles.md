# Day 05 – More, Less, History, and Dotfiles

## Objective
Learn efficient command line navigation using `more`, `less`, tab completion, shell history, and hidden configuration files. 
Practice reusing commands and inspecting system logs.

---

## Commands Practiced

### Viewing Files with `more` and `less`
```bash
man more
more /var/log/auth.log
less /var/log/auth.log
````

Key `less` navigation:

* `q` quit
* `/text` search
* `n` next match
* `Shift+G` jump to bottom
* `g` jump to top

---

### Tab Completion

Tested command and path completion:

```bash
le<TAB>
less /var/log/a<TAB>
less /var/log/<TAB>
```

---

### Command History

Viewed and reused previous commands:

```bash
history
history 10
!95
sudo !!
```

Used:

* Up arrow to scroll commands
* `history` to list cached commands
* `sudo !!` to rerun the last command with sudo

---

### Inspecting Protected Files

```bash
less /etc/shadow
sudo less /etc/shadow
```

---

### Hidden Files and Dotfiles

Listed hidden files in home directory:

```bash
ls -a
```

Viewed common dotfiles:

```bash
less .bash_history
less .bashrc
```

Files observed:

* `.bashrc`
* `.bash_history`
* `.profile`
* `.ssh/`

---

### Editing with Nano

Opened and edited shell configuration:

```bash
nano .bashrc
```

Used Nano for basic file editing and saving.

---

## Screenshots

See `/screenshots` directory for visual confirmation of tasks.
