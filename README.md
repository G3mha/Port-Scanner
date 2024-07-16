# Port Scanner (Python)

## Description
A simple yet efficient port scanner built in Python, designed to scan and report open ports on a specified host. Utilizing multi-threading for speed and the `colorama` library for enhanced terminal output, this script offers clear and colored status messages for open and closed ports. Scan results are saved in a JSON file for easy review.

## Features
- **Single-threaded port scanning**: Scans a range of ports on a given host.
- **Color-coded output**: Uses `colorama` to distinguish between open (green) and closed (red) ports.
- **Service identification**: Attempts to identify services running on open ports.
- **Configurable output**: Option to show only open ports.
- **Result logging**: Saves scan results to `port_scan_results.json`.

## Usage
1. Clone the repository.
2. Run `main.py`.
3. Follow the prompts to enter the target IP address or hostname, start and end port numbers, and whether to display only open ports.
4. View the scan results in the terminal or in `port_scan_results.json`.

## Requirements
- Python 3.x
- `colorama` library

## Installation
```bash
pip install -r requirements.txt
```

Or

```bash
pip install colorama
```

## Example
```bash
python main.py
```

## License
This project is licensed under the AGPL License.
