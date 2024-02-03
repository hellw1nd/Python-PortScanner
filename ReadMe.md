# Basic Port Scanner Tool in Python

## Introduction

This is a basic port scanner tool implemented in Python. It allows you to scan for open ports on a specified target host within a customizable port range.

## Features

- Scan for open ports on a target host.
- Specify a customizable range of ports to scan.
- Simple and easy-to-use.

## Prerequisites

- Python 3.x installed on your system.

## Usage

1. Clone the repository or download the Python script.

    ```bash
    git clone https://github.com/hellw1nd/Python-PortScanner
    ```

2. Navigate to the directory.

    ```bash
    cd your-port-scanner
    ```

3. Run the script with the target host and port range as arguments.

    ```bash
    python3 scanner.py <target-ip>
    ```

    Example:

    ```bash
    python3 scanner.py example.com 
    ```

4. View the results.

    The script will display a list of open ports on the target host within the specified range.

## Script Details

- The script uses the `socket` module in Python to check for open ports.
- The default port range in the script is set from 50 to 85, but you can customize it based on your needs.
- The script provides a simple banner and displays the time the scan started.

## Disclaimer

This tool is intended for educational purposes only. Do not use it on systems or networks without proper authorization.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
