# DALL-E 3 Image Generator Script

This Python script allows users to interact with OpenAI's DALL-E 3 API to generate images based on textual prompts. It prompts the user to enter a text, submits this text to the DALL-E 3 model, and if successful, returns the URL of the requested image.

NOTE: OpenAI API documentation may change in the future. For information, visit the official OpenAI site for developers. 

## Important Note
The images generated by the DALL-E 3 API are typically available for a short period of time, approximately 15 minutes, before they are no longer accessible via the URL.

## Authentication
The OpenAI API uses API keys for authentication. Visit your [API Keys page](https://platform.openai.com/account/api-keys) to retrieve the API key you'll use in your requests.

## Features

- Interactive prompt for user input.
- Integration with OpenAI's DALL-E 3 API.
- Returns the URL of the generated image based on the user's text input.

## Prerequisites

Before running this script, ensure you have the following installed:

- Python (3.x or above)
- `requests` library for Python (for making HTTP requests)
- An API key from OpenAI for DALL-E 3 access

## Installation

1. Install Python from [Python's official website](https://www.python.org/downloads/).
2. Install the `requests` library using pip:
3. Set up an environment variable `OPEN_API_KEY2` with your OpenAI API key. 

## Usage

Run the script in a Python environment. Follow the interactive prompts to enter your text for image generation and receive the image URL.


## OpenAI DALL-E 3 API Documentation

For more details about the DALL-E 3 API and its capabilities, please refer to the official [OpenAI DALL-E 3 API documentation](https://platform.openai.com/docs/guides/images/introduction).

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ffm5113/python_dalle3_local/blob/main/LICENSE) file for details.
