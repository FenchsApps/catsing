# Documentation for `catsing`

`catsing` is an interactive Bash script that draws ASCII art of a cat and allows you to interact with it. The script plays meow sounds and displays fun messages.

---

## Installation

### For Gentoo
1. Add the overlay containing the `catsing` package.
2. Install the package:
   ```bash
   emerge app-misc/catsing
   ```

### For Arch Linux
1. Install the package from AUR:
   ```bash
   yay -S catsing
   ```

### Manual Installation
1. Download the script and the `cat.wav` file:
   ```bash
   git clone https://github.com/yourusername/catsing.git
   cd catsing
   ```
2. Make the script executable:
   ```bash
   chmod +x catsing.sh
   ```
3. (Optional) Copy the script and sound file to system directories:
   ```bash
   sudo cp catsing.sh /usr/local/bin/catsing
   sudo mkdir -p /usr/share/catsing
   sudo cp cat.wav /usr/share/catsing/
   ```

---

## Usage

Run the script with the command:
```bash
catsing
```

### Main Commands
1. **`catsing --stay`**:
   - The cat grows larger, and the text disappears.

2. **`catsing --meow`**:
   - The cat "meows" three times (plays the `cat.wav` sound).
   - After that, a message is displayed: "My computer has been hacked by a cat!".
   - Example output:
     ```
     Meow!
     Meow!
     Meow!

---

## Examples

### Running and Interacting
1. Run the script:
   ```bash
   catsing
   ```
2. Choose a command:
   - Enter `1` to enlarge the cat.
   - Enter `2` to make the cat meow.

### Running Commands Directly
You can pass the command directly:
```bash
catsing --meow
```
or
```bash
catsing --stay
```

---

## Requirements

- **Bash**: The script requires a Bash interpreter.
- **Sound System**:
  - To play sounds, `paplay` (PulseAudio) or `aplay` (ALSA) is required.
- **Sound File**: The `cat.wav` file must be in the same directory as the script or in `/usr/share/catsing/`.

---

## License

`catsing` is distributed under the **GNU General Public License v2 (GPL-2)**. You are free to use, modify, and distribute this script.

---

## Author

- **Your Name**: [Your GitHub](https://github.com/FenchsApps)
- **Repository**: [catsing](https://github.com/FenchsApps/catsing)

---

## Acknowledgments

- Thanks to everyone who inspired the creation of this script.
- Thanks to the community for their support and ideas.

---
