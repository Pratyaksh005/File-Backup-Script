
# File Backup Utility

A simple Python-based file backup application with a graphical user interface (GUI). This utility allows you to back up files from one directory to another, with features such as a progress bar, pause/unpause functionality, and the ability to cancel the backup process.

---

## Features

- **Backup Files**: Copy files and directories from a source folder to a backup folder.
- **Progress Bar**: Visualize the progress of the backup operation.
- **Pause/Unpause**: Pause and resume the backup process at any time.
- **Cancel**: Stop the backup process mid-operation.
- **Error Handling**: Alerts for invalid inputs or unexpected errors.

---

## Requirements

- Python 3.8 or higher
- Required libraries:
  - `tkinter` (comes pre-installed with Python)
  - `shutil` (comes pre-installed with Python)
  - `os` (comes pre-installed with Python)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Pratyaksh005/file-backup-utility.git
   cd file-backup-utility
   ```

2. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).

---

## Usage

1. Run the `gui.py` script:
   ```bash
   python gui.py
   ```

2. Use the graphical interface to:
   - Select a source directory (files to back up).
   - Select a backup directory (destination folder).
   - Start the backup process.
   - Pause, resume, or cancel the backup as needed.

---

## File Structure

```
file-backup-utility/
│
├── backup.py   # Contains the backup logic with pause/cancel functionality
├── gui.py      # Provides the graphical user interface
├── README.md   # Project documentation
```

---

## Screenshots
<img width="724" alt="Gui" src="https://github.com/user-attachments/assets/3c6f2f90-2580-4088-a6ca-ee66b3a3c419">

---

## Known Issues

- Large file sizes may slow down the estimated time calculations.
- Cancelling a backup in progress may leave partially copied files in the destination folder.

---

## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature-name'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- Python `tkinter` documentation: [Tkinter](https://docs.python.org/3/library/tkinter.html)
- Python `shutil` documentation: [Shutil](https://docs.python.org/3/library/shutil.html)
