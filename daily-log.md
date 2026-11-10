# Cybersecurity Learning Log

## 7 November 2026

### What I did today
- Created my cybersecurity learning-log repository.
- Practiced basic Linux commands in Ubuntu VirtualBox.

### What I learned
- I learned how to create a GitHub repository and add a Markdown file.
- `pwd` shows the current folder.
- `ls` lists files and folders.
- `whoami` shows the current username.
- `cd` moves into a folder.
- `cd ..` goes back one folder.
- `mkdir folder-name` creates a folder.
- `rmdir folder-name` removes an empty folder.
- Linux is case-sensitive: `Desktop` and `desktop` are different.
- Spaces in folder names need quotation marks.

### What confused me
- I am still getting used to GitHub’s interface.
- I need more practice moving between folders using `cd`.

### Tomorrow’s task
- Practice creating, viewing, renaming, copying, and deleting files using `touch`, `cat`, `nano`, `mv`, `cp`, and `rm`.

### 8 November 2026 — Linux files
- Practiced touch, nano, cat, cp, mv, and rm.
- Created linux-notes.txt and copied it as backup.txt.
- Renamed backup.txt to old-notes.txt.
- Deleted old-notes.txt using rm.
- Learned that rm permanently deletes files.

### 9 November 2026 — Progress review

- Practiced Linux navigation: pwd, ls, cd, cd .., and cd ~.
- Practiced file operations: touch, nano, cat, cp, mv, and rm.
- Practiced folder operations: mkdir and rmdir.
- Learned basic Linux permissions: read, write, and execute.
- Used ls -l and chmod to view and change permissions.
- Changed Ubuntu’s date and time settings.
- Created security-practice and notes.txt as practice.

### 10 November 2026 — Linux permissions

## What I practiced
- Created `security-practice` using `mkdir security-practice`.
- Entered the folder using `cd security-practice`.
- Confirmed my location using `pwd`.
- Created `notes.txt` using `touch notes.txt`.
- Viewed file permissions using `ls -l notes.txt`.

## What I learned
- `ls -l` shows detailed information about files and folders.
- A line beginning with `-` means a regular file.
- A line beginning with `d` means a directory/folder.
- `r` means read permission.
- `w` means write permission.
- `x` means execute permission.
- For a folder, `x` means permission to enter or search the folder.
- Permissions are divided into owner, group, and others.
- `u` means user/owner.
- `g` means group.
- `o` means others.
- `chmod u-w file` removes write permission from the owner.
- `chmod u+w file` gives write permission back to the owner.

## Example
- `-rw-r--r--` means:
  - Owner can read and write.
  - Group can read only.
  - Others can read only.
  - Nobody can execute the file.

## What confused me
- At first, I thought `mv` was used to move myself into a folder, but `mv` moves or renames files and folders. `cd` changes my current folder.
