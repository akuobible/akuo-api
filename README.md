# Akuo API Swagger UI

This project provides a local Swagger UI for exploring and testing the [Akuo API](AkuoAPI.yaml).

## Project Structure

- `index.html` – Loads Swagger UI and displays the API documentation from `AkuoAPI.yaml`.
- `AkuoAPI.yaml` – OpenAPI 3.0 specification for the Akuo API.
- `.nojekyll.txt` – Prevents Jekyll processing on GitHub Pages.
- `LICENSE` – MIT License.

## Usage

### Local Preview

To view the Swagger UI locally:

1. Start a simple HTTP server in the project directory. For example, with Python 3:
   ```sh
   python -m http.server 8000
   ```
2. Open your browser and go to [http://localhost:8000](http://localhost:8000).

You will see the interactive documentation for the Akuo API.

### API Documentation

- The API specification is defined in [`AkuoAPI.yaml`](AkuoAPI.yaml).
- The UI uses [Swagger UI](https://swagger.io/tools/swagger-ui/) via CDN.

## License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE) for details.