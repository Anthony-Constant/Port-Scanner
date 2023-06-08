# Port Scanner

The Port Scanner is a Python script that allows users to scan a target IP address and determine which ports are open. This script utilizes multi-threading to optimize the scanning process and automatically logs the open ports to a local file.

## How It Works

1. Enter the target IP address to be scanned.
2. The script will connect to the IP address and check if each port is open.
3. Once the scan is complete, the script will display the open ports in the terminal.
4. The script will also create a `port_logs.txt` file and write the open ports for automation storage.

## Features

- Scan a target IP address for open ports.
- Utilize multi-threading for faster scanning.
- Automatically log the open ports to a `port_logs.txt` file.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/port-scanner.git`
2. Open the project in your preferred code editor.
3. Run the `Port_Scanner.py` script.
4. Enter the target IP address when prompted.
5. Once the scan is complete, the open ports will be displayed in the terminal.
6. The open ports will also be logged in the `port_logs.txt` file.

## Dependencies

The Port Scanner script requires the following dependencies:

- Python 3.x
- `socket` library
- `threading` library
- `concurrent.futures` library
- `os` library

Install the required dependencies using pip:
- pip install socket threading concurrent.futures


## Customization

You can customize the script by modifying the following:

- `Port_Scanner.py`: Customize the scanning process, thread pool size, and modify the log file name.

## References

- [Python socket library documentation](https://docs.python.org/3/library/socket.html)
- [Python threading library documentation](https://docs.python.org/3/library/threading.html)
- [Python concurrent.futures library documentation](https://docs.python.org/3/library/concurrent.futures.html)
- [Palo Alto Networks - What is a Port Scan?](https://www.paloaltonetworks.com/cyberpedia/what-is-a-port-scan)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

The Port Scanner script was created by [Anthony Constant](https://anthonyconstant.co.uk/).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).




