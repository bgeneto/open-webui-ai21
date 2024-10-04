# AI21 Studio Manifold Pipe Function for Open WebUI

## Overview

The **AI21 Studio Manifold Pipe** is a open-webui function designed to interact with the AI21 Studio API, facilitating seamless communication and data processing with AI models provided by AI21. 
This repository contains a single Python file that implements a `Pipe` class to handle API requests and responses, ensuring efficient and secure interactions with the AI21 models.

## Features

- **Modular Design**: The code is structured to adhere to SOLID principles, ensuring that each class and method has a single responsibility.
- **Dependency Injection**: The `AI21Service` class is designed to be flexible and testable by injecting dependencies.
- **Validation**: Comprehensive validation methods ensure that model IDs and message formats are correct before processing.
- **Streamlined Error Handling**: Specific error types are used for better clarity and debugging.
- **Readable and Maintainable Code**: The code is broken down into smaller, focused methods to enhance readability and maintainability.

## Requirements

- Open WebUI v0.3.17
- `pydantic`
- `ai21`
- Environment Variable: `AI21_API_KEY`

## Installation

1. Install this function in your Open WebUI instance directly via this [link](https://openwebui.com/f/bgeneto/ai21_studio) or paste the source code in Workspaces --> Functions.

## Usage

Just select the "AI21 Studio: Jamba 1.5 Mini" or "AI21 Studio: Jamba 1.5 Large" model in the main open-webui chat window.

## Debugging

The `DEBUG` flag can be set to `True` to enable detailed logging for debugging purposes.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to AI21 for providing the powerful AI models and API.
- Inspired by the need for clean, maintainable, and efficient code in AI-driven applications.

---

For any questions or support, please open an issue on GitHub or contact the maintainer directly.
