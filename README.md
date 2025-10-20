# Gamma Control Script

This Bash script allows users to adjust the gamma settings of their display in real-time. By utilizing keyboard inputs, users can increase or decrease the gamma value, enhancing their viewing experience based on personal preferences or environmental lighting conditions.

## Features

- **Adjust Gamma**: Increase or decrease the gamma value with simple keypresses.
- **Cursor Visibility Control**: Hides the cursor while the script is running for a cleaner interface.
- **Responsive Input Handling**: Supports various input formats, including arrow keys and specific letters for adjustments.

## Requirements

- **Operating System**: Linux-based (Debian, Ubuntu, etc.)
- **Dependencies**: 
  - `xgamma` - Ensure that this package is installed on your system as it is responsible for modifying the gamma settings.

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/gamma-control-script.git
cd gamma-control-script
```

    Make the script executable:
	`chmod +x gamma-control-script.sh`

Run the script:

```bash
    ./gamma-control-script.sh
```

## Usage

Upon running the script, a simple menu will be displayed. You can adjust your gamma settings using the following keys:

    1 / 'w' / 'up' / 'pgup': Increase gamma
    2 / 's' / 'down' / 'pgdown': Decrease gamma
    Escape: Exit the script

The current gamma value will be displayed, allowing you to keep track of your adjustments.


## User Interface

The main() function clears the screen and presents the current gamma value along with the interactive options, looping until the user decides to exit.

---

This project is licensed under the MIT License - see the LICENSE file for details.
