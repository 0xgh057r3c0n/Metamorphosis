# Metamorphosis: The Evolution of Identity

This tool allows you to extract EXIF metadata from images, providing valuable insights like camera model, date taken, and other details embedded within the image file. It is designed to help you understand the evolution of identity as captured in digital images.

## Features

- Extracts EXIF metadata from images in various formats.
- Validates image files and checks for EXIF data.
- Displays EXIF data in a user-friendly terminal output.
- Uses color formatting for enhanced readability.

## Requirements

- Python 3.x
- The following Python libraries:
  - `Pillow`: For image file handling.
  - `exifread`: For extracting EXIF metadata.
  - `colorama`: For terminal text formatting.

To install the necessary dependencies, run:

```bash
pip install Pillow exifread colorama
```

## Installation

1. **Clone the repository:**

   Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/0xgh057r3c0n/Metamorphosis.git
   cd Metamorphosis
   ```

2. **Install dependencies:**

   Ensure you have the necessary dependencies by running the following command:

   ```bash
   pip install -r requirements.txt
   ```

   Alternatively, you can manually install the dependencies:

   ```bash
   pip install Pillow exifread colorama
   ```

## Usage

1. **Run the script:**

   Once the dependencies are installed, you can run the script `exif.py` using the following command:

   ```bash
   python3 exif.py
   ```

2. **Provide the image file name:**

   The script will prompt you to input the image file name. Ensure the image file is in the same directory as the script, or provide the full path to the image file.

3. **View EXIF Data:**

   The script will display EXIF metadata of the image file in a formatted output. If no EXIF data is found, an appropriate message will be shown.

### Example Output

```plaintext
Photo Name: example.jpg
Valid Image!

EXIF Data of example.jpg:
----------------------EXIF Info----------------------
Image DateTime: 2024:12:10 15:30:00
Image Make: Canon
Image Model: EOS 5D Mark IV
...
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The tool uses the `exifread` library for extracting EXIF data.
- Color output is achieved using `colorama`.
- Special thanks to the Python and open-source community.

## Author

- **0xgh057r3c0n (Gaurav Bhattacharjee)**: Creator of Metamorphosis

---

Thank you for using the Metamorphosis tool! If you have any issues or suggestions, feel free to open an issue or a pull request.
