# Prometheus

![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)
![Python](https://img.shields.io/badge/python-3.6+-green.svg)

Prometheus is a powerful system information and hardware identification tool built in Python. It provides detailed hardware, memory, CPU, network, and storage information in an easy-to-use command-line interface.

## Features

- **Hardware Identification**: Get detailed hardware identifiers for system components
- **System Analysis**: View comprehensive information about your system
- **Network Analysis**: Display network adapters and connection statistics
- **Storage Information**: Monitor drives, partitions, and disk I/O
- **CPU Monitoring**: View CPU details and per-core usage statistics
- **Memory Analysis**: Track RAM usage and top memory-consuming processes
- **Export Capabilities**: Export all hardware information to text files
- **Command History**: Keep track of your command usage
- **Customizable UI**: Change themes to suit your preferences

## Screenshots

*[Add screenshots here]*

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/prometheus.git
```

2. Navigate to the directory:
```bash
cd prometheus
```

3. Install required dependencies:
```bash
pip install colorama psutil tabulate
```

## Usage

Run as administrator/with elevated privileges:

```bash
python prometheus.py
```

### Available Commands

#### Built-in Commands
- `help` - Display help menu
- `clear` - Clear the terminal screen
- `exit` - Exit Prometheus
- `version` - Display version information
- `sysinfo` - Display system information

#### Hardware Commands
- `hwid` - Display hardware identifiers
- `drives` - Display storage devices info
- `cpu` - Display CPU information
- `memory` - Display RAM information
- `network` - Display network adapters
- `export` - Export all hardware info to file

#### Utility Commands
- `history` - Show command history
- `theme` - Change UI theme
- `banner` - Show Prometheus banner

Any other input will be executed as a system command.

## Requirements

- Python 3.6+
- Administrator/root privileges
- Required packages: colorama, psutil, tabulate (auto-installed if missing)

## Supported Platforms

- Windows
- Linux
- macOS (limited functionality)

## License

[Add your license here]

## Contributing

[Add contribution guidelines if applicable]

## Disclaimer

This tool is intended for legitimate system diagnostics and hardware identification purposes only. Always use responsibly and ethically.
