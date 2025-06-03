# Akuo API Swagger UI

This project documents the [Akuo API](AkuoAPI.yaml) and publishes to Swagger UI from GitHub Pages.

## Project Structure

- `index.html` – Loads Swagger UI and displays the API documentation from `AkuoAPI.yaml`.
- `AkuoAPI.yaml` – OpenAPI 3.0 specification for the Akuo API.
- `.nojekyll.txt` – Prevents Jekyll processing on GitHub Pages.
- `LICENSE` – MIT License.

## Usage

### View the API in Swagger from GitHub Pages

[APM Akuo API on Swagger](https://akuobible.github.io/akuo-api/)

### Local Preview

To view the Swagger UI locally:

1. Start a simple HTTP server in the project directory. For example, with Python 3:
   ```sh
   python -m http.server 8000
   ```
2. Open your browser and go to [http://localhost:8000](http://localhost:8000).

You will see the interactive Swagger documentation for the Akuo API.

### API Documentation

- The API specification is defined in [`AkuoAPI.yaml`](AkuoAPI.yaml).
- The UI uses [Swagger UI](https://swagger.io/tools/swagger-ui/) via CDN as defined in index.html.

### Deploy on GitHub Pages

- From the [akuobible/akuo-api](https://github.com/akuobible/akuo-api) GitHub repo
- Click Settings → Pages
- Under Source dropdown, choose main
- Click Save
- After a minute or two, your site will be live at: [https://akuobible.github.io/akuo-api/](https://akuobible.github.io/akuo-api/)
- Any updates to the repo will trigger an automatic rebuild

## License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE) for details.