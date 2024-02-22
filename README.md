<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo" />
</div>

Welcome to Python Server Client, a powerful and efficient tool designed to streamline server-client communications in Python. This tool simplifies the management of your API requests, whether you're working with token-based or session-based authentication.

Explore the [documentation](https://grow.empress.eco/) for a more detailed understanding of the project. If you encounter any bugs or want to request a feature, please do so [here](https://github.com/empress-eco/python_server_client/issues).

## About Python Server Client

Python Server Client is designed to simplify the communication process between servers and clients, offering an efficient way to handle authentication and enabling easy invocation of GET and POST endpoints. With built-in support for fetching single or multiple resources via the Documents API and Pagination API, this tool is an essential for Python developers looking to save time and reduce code complexity.

### Key Features

- Supports both Token-based and Session-based authentication.
- Simplified invocation of GET and POST endpoints.
- Offers a Documents API for fetching single or multiple resources.
- Built-in support for Pagination API.

## Getting Started

To get the Python Server Client up and running, follow these steps:

### Prerequisites

Ensure you have Python and pip installed on your system. If not, follow the instructions [here](https://www.python.org/downloads/) to install Python and pip.

### Installation

Clone the repository using this [link](https://github.com/empress-eco/python_server_client.git). Install the Python Server Client using pip by running the following command in your terminal:

```sh
pip install py-Empress-client
```

## Usage

Here are some examples to guide you on how to use the Python Server Client:

### Token-based authentication

```python
from Empress_client import EmpressRequest
client = EmpressRequest(url="http://localhost:8002", api_key="API_KEY", api_secret="API_SECRET")
client.get("method_name")
client.post("method_name")
```

### Session-based authentication

```python
from Empress_client import EmpressRequest
client = EmpressRequest(url="http://localhost:8002", username="user", password="password")
```

## Contributing

We appreciate and welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Your interest in making this tool better is appreciated!

## License and Acknowledgements

### License

This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements

Special thanks to the Empress Community for their pioneering work and ongoing support. The innovation and dedication of the Empress Community have been instrumental in building the essential tools that power this project. We are profoundly grateful for their foundational contributions.