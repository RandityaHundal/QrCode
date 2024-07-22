# QR Code Generator

This Python script generates a QR code from a given website link and saves it as an image file.

## Requirements

- Python 3.x
- `qrcode` library

## Installation

1. Install Python 3.x from [python.org](https://www.python.org/).
2. Install the `qrcode` library using pip:

    ```sh
    pip install qrcode pillow
    ```

## Usage

1. Run the script:

    ```sh
    python qr_code.py
    ```

2. Enter the website link when prompted:

    ```
    Link: https://example.com
    ```

3. Enter the name of the file to save the QR code image:

    ```
    Name of the file: example_qr
    ```

4. The QR code image will be saved with the specified name in the current directory.

## Example

```sh
python qr_code.py
Link: https://example.com
Name of the file: example_qr
