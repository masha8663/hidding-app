# hidding-app
"This app allows users to securely hide sensitive files or information within images using steganography techniques. It ensures privacy by embedding data in a way that remains undetectable to the human eye."
# Hiding-App

## Overview
This app allows users to securely hide sensitive files or information within images using steganography techniques. It ensures privacy by embedding data in a way that remains undetectable to the human eye.

## Features
- Hide text or files inside images.
- Extract hidden data from encoded images.
- Uses steganography for secure data concealment.
- Simple and user-friendly interface.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/masha8663/hiding-app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd hiding-app
   ```
3. Install dependencies:
   ```bash
   pip install pillow numpy opencv-python
   ```

## Usage
### Encoding (Hiding Data)
```python
from steganography import encode_image
encode_image("input.png", "Your secret message", "encoded.png")
```

### Decoding (Extracting Data)
```python
from steganography import decode_image
print(decode_image("encoded.png"))
```

## Contributing
Feel free to contribute by submitting issues or pull requests.

## Author
Created by **umme rubab**

