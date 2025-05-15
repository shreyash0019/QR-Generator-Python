# QR Code Generator in Python

This is a simple Python script to generate a QR code using the `qrcode` library.

## Installation

Ensure you have Python installed on your system, then install the required package:

```sh
pip install qrcode[pil]
```

## Usage

Use the following Python script to generate a QR code:

```python
import qrcode

generate_image = qrcode.make("paste link of web page or any particular thing , here. You want to generate qr code.")
generate_image.save('image.png')
```

## Output

Running the script will generate a `image.png` file containing the QR code, which can be scanned to open the provided  link.

## Repository

Find the complete project on GitHub: [QR-Generator-Python](https://github.com/shreyash0019/QR-Generator-Python.git)

