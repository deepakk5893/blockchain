# Simple Blockchain Implementation with Flask

This is a basic implementation of a blockchain using Python and Flask.

## Description

The code includes a simple blockchain class (`BlockChain`) which creates blocks, performs proof of work, and validates the blockchain. Additionally, there is a Flask application providing API endpoints for mining new blocks, getting the full chain, and checking the validity of the blockchain.

## Requirements

- Python 3.x
- Flask

## How to Use

1. Clone the repository or copy the code into your project.
2. Install Flask if you haven't already (`pip install Flask`).
3. Run the Flask application by executing the Python script.
4. Use API endpoints to interact with the blockchain:
    - `/mine_block`: Mines a new block.
    - `/get_chain`: Retrieves the full blockchain.
    - `/is_valid`: Checks the validity of the blockchain.

## Code Structure

- `BlockChain` class: Implements the basic functionalities of a blockchain.
- `mine_block()`: Endpoint to mine a new block.
- `get_chain()`: Endpoint to get the full chain.
- `is_valid()`: Endpoint to check the validity of the blockchain.

## API Endpoints

### Mine Block
- **Method**: GET
- **Endpoint**: `/mine_block`
- **Description**: Mines a new block on the blockchain.

### Get Chain
- **Method**: GET
- **Endpoint**: `/get_chain`
- **Description**: Retrieves the full blockchain.

### Check Validity
- **Method**: GET
- **Endpoint**: `/is_valid`
- **Description**: Checks the validity of the blockchain.

## Usage

- Start the Flask server (`app.run(host='0.0.0.0', port=6000)`).
- Use tools like cURL or Postman to interact with the provided API endpoints.

## Note

This implementation is for educational purposes and lacks many features found in production-ready blockchains.