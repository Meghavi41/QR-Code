# QR-Code
his script loads product data from an Excel file and generates a QR code for each product based on its details. Each QR code is saved as a PNG file named after the product's serial number.
# QR Code Generator for Product Details

This project generates QR codes for product details stored in an Excel file. Each QR code contains information about a product, such as its serial number, color, date of manufacturing, and sweep size.

## Features

- Load product details from an Excel file
- Generate QR codes containing product information
- Save QR codes as PNG images

## Requirements

- Python 3.x
- pandas
- qrcode

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/your_repository.git
    cd your_repository
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas qrcode[pil]
    ```

## Usage

1. Place your product details in an Excel file named `products.xlsx` in the project directory. The Excel file should have the following columns:
    - `Serial Number`
    - `Color`
    - `Date of Manufacturing`
    - `Sweep Size`

2. Run the script to Execute the script to generate QR codes for each product in the Excel file. The script will create PNG images for each product and save them in the same directory.

'''bash
python generate_qr_codes.py
