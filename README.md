# CrackFtp 🔒

![CrackFtp](https://img.shields.io/badge/CrackFtp-v1.0-blue)

Welcome to **CrackFtp**, a powerful script designed for security professionals and ethical hackers. This tool allows you to test FTP login credentials efficiently and receive alerts on successful logins via Telegram. With this script, you can enhance your security assessments and streamline your testing process.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Telegram Notifications](#telegram-notifications)
- [Supported Protocols](#supported-protocols)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Releases](#releases)

## Features

- **Mass FTP Checking**: Test multiple credentials against secure domains.
- **Brute Force Capability**: Efficiently attempt various combinations to find valid logins.
- **Telegram Alerts**: Receive instant notifications for successful logins.
- **Command-Line Interface**: Simple and effective interface for quick execution.
- **Customizable**: Modify settings to suit your testing needs.

## Installation

To get started with CrackFtp, follow these simple steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Christian-Rivera134/CrackFtp.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd CrackFtp
   ```

3. **Install Required Packages**:
   Ensure you have Python installed. You can install the necessary packages using:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To use CrackFtp, run the script from your command line. Here’s the basic command structure:

```bash
python crackftp.py -u <username_file> -p <password_file> -t <target>
```

- `-u <username_file>`: Specify the file containing usernames.
- `-p <password_file>`: Specify the file containing passwords.
- `-t <target>`: Provide the FTP server address.

### Example

```bash
python crackftp.py -u usernames.txt -p passwords.txt -t ftp.example.com
```

## Configuration

Before running the script, you may need to configure certain parameters. Open the `config.py` file to adjust settings such as:

- **Timeout Settings**: Modify the timeout for connection attempts.
- **Logging Options**: Choose whether to log attempts to a file.

## Telegram Notifications

To set up Telegram notifications:

1. **Create a Bot**: Use the BotFather on Telegram to create a new bot and obtain the API token.
2. **Get Your Chat ID**: Send a message to your bot and use a tool to find your chat ID.
3. **Update the Config**: Insert your API token and chat ID into the `config.py` file.

## Supported Protocols

CrackFtp primarily supports the FTP protocol. Future updates may include support for additional protocols such as FTPS and SFTP.

## Contributing

We welcome contributions to CrackFtp. If you would like to help improve the script, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**.
4. **Commit Your Changes**:
   ```bash
   git commit -m "Add your message"
   ```
5. **Push to Your Branch**:
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the contributors and community members who helped improve CrackFtp.
- Special thanks to the creators of the libraries and tools used in this project.

## Releases

For the latest version of CrackFtp, please visit the [Releases](https://github.com/Christian-Rivera134/CrackFtp/releases) section. Download the latest file, execute it, and start testing your FTP credentials today.

## Conclusion

CrackFtp is a valuable tool for security professionals. It streamlines the process of testing FTP credentials and enhances your security assessments. Download the latest version from the [Releases](https://github.com/Christian-Rivera134/CrackFtp/releases) section and start using it today.

Feel free to reach out with any questions or feedback. Happy hacking!