# SimpleChain-Educational-Demo

SimpleChain is a minimalistic blockchain implementation in Python designed for educational purposes. This project aims to provide a basic understanding of the core concepts of blockchain technology, such as block structure, hashing, and maintaining the integrity of the chain.

## Features

- Basic block structure and creation
- Genesis block initialization
- SHA-256 hashing for block data
- Automated block creation every 10 seconds
- Saving the blockchain to a .txt file

## Installation

To run SimpleChain, ensure you have Python 3.6 or higher installed. No additional packages are required.

1. Clone the repository:

```bash
git clone https://github.com/your_username/SimpleChain-Educational-Demo.git
```

2. Navigate to the project directory:

```bash
cd SimpleChain-Educational-Demo
```

3. Run the script:

```bash
python simplechain.py
```

## Usage

Upon starting the script, press any key to launch the node. SimpleChain will begin creating blocks every 10 seconds and print the block details to the console. The blockchain will be saved to a file called `blockchain.txt` after each new block is added.

## Limitations

This implementation is intended for educational purposes only and is not suitable for production use. SimpleChain has several limitations, including:

- Lack of a consensus algorithm
- Absence of a distributed network
- No transaction validation or smart contract functionality
- Limited security measures

Please refer to the project's white paper for a more in-depth explanation of SimpleChain's functionality and limitations.

## Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

- Fork the repository
- Create a new branch with a descriptive name (e.g., implement-proof-of-work)
- Commit your changes to the branch
- Push the branch to your forked repository
- Create a pull request to merge your changes into the main repository

## License

This project is released under the MIT License.
