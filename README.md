
# Anthropica API Integration with Flask

This project is a Flask application that integrates with the Anthropica API to generate responses based on user input. It provides an API endpoint for generating responses using the Anthropica API.

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repository.git
   ```
2. Install dependencies from `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```
3. Obtain your Anthropica API key and update `api_key=""` in `app.py` with your API key.

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```
2. Send a POST request to `http://localhost:5000/generate_response` with JSON data containing a 'text' field to generate a response.

Example:
```json
{
  "text": "Why is the sky blue?"
}
```

3. The server will respond with a JSON object containing the generated response.

## API Endpoint

- **POST** `/generate_response`: Generates a response using the Anthropica API.

## Dependencies

- Flask
- anthropic

## Contributing

Feel free to contribute to this project by submitting pull requests or reporting issues.


## Acknowledgements

- [Anthropica API](https://anthropica.co/)
- Flask Community

## Contact

For questions or feedback, contact [Harish](harish.shanu009@gmail.com).

