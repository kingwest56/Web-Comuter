# Define the content of the README file
readme_content = """# Computer Store Website

## Overview
This project is a simple static website for a computer store. It includes pages for:
- Home
- Products (to be developed)
- About Us
- Contact

## Files
- `index.html`: Main page of the website.
- `styles.css`: Stylesheet for the website.
- `script.js`: JavaScript file for functionality.
- `about.html`: About Us page with company information.
- `contact.html`: Contact page with email, phone, and address details.

## Usage
1. Download all files and keep them in the same directory structure.
2. Open `index.html` in your web browser to start exploring the website.

## Future Development
- Add a `products.html` page to showcase available products.
- Include dynamic features like a shopping cart using JavaScript or a backend framework.

## License
This project is free to use for educational and personal purposes.

## Contact
For any issues or suggestions, please contact us at support@computerstore.com.
"""

# Save the README file
readme_path = os.path.join(directory_path, "README.md")
with open(readme_path, "w") as f:
    f.write(readme_content)

readme_path
