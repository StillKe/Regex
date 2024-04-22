# HTML Price Extractor

This Python script extracts prices from HTML content using regular expressions.

## Usage

1. Ensure you have Python installed on your system.
2. Run the script `extract_price_from_html.py`.
3. Provide the HTML content containing the price.
4. The script will extract and display the price.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

css
Copy code

You can save this content in a file named `README.md` in your project direct

## Example

```python
import re

html_content = '<p>Price : 19.99$</p>'

m = re.match('<p>(.+)<\/p>', html_content)
if m:
    print(m.group(1))

