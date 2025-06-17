# A secure firewall against reverse shell and reverse proxy 

## Overview
Simple, Secure and Rusty 

## Prerequisites
Before you begin, ensure you have Rust installed on your system. Follow the [Rust Installation Guide](https://www.rust-lang.org/tools/install) for guidance.

## Getting Started
Clone this repository and navigate into the project directory:

    git clone https://github.com/Amirhousain110/Apollyon.git
    cd Apollyon
    cargo build -r
    ./target/release/apo  

## Features
- **Rule Definition**: Define rules based on source IP, destination port, and other criteria.
- **Rule Management**: Add, remove, and list firewall rules.
- **Iptables Integration**: Update iptables based on defined rules.
- **Command-Line Interface**: Easy-to-use CLI for managing the firewall.
- **Packet Processing**: Process incoming packets and apply rules.
- **Logging**: Log accepted and dropped packets for monitoring.
- **Error Handling**: Gracefully handle errors and provide informative messages.

## Contributing
Contributions to this project are welcome. Please submit a pull request or open an issue to suggest improvements.

## License
This project is licensed under the MIT
