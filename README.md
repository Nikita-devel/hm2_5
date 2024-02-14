# Asynchronous HTTP Requests with aiohttp

This Python script demonstrates making asynchronous HTTP requests using the `aiohttp` library. It fetches content from multiple URLs concurrently.

## Usage

1. Make sure you have Python 3.7 or later installed on your system.

2. Install required dependencies:

    ```bash
    pip install aiohttp
    ```

3. Clone the repository:

    ```bash
    git clone https://github.com/Nikita-devel/asynchronous-http-requests.git
    ```

4. Navigate to the project directory:

    ```bash
    cd asynchronous-http-requests
    ```

5. Run the script:

    ```bash
    python script.py
    ```

6. View the output:

    The script will start fetching content from the specified URLs asynchronously, and the output will be displayed in the console.

## Script Overview

### `script.py`

This script performs asynchronous HTTP requests using `aiohttp`:

- `urls`: List of URLs to fetch asynchronously.
- `main()`: Asynchronous function to handle HTTP requests.
- `try-except` block: Handles connection errors and invalid URLs.
- `if __name__ == '__main__'`: Runs the `main()` function.

## Example

```bash
pip install aiohttp
python script.py
