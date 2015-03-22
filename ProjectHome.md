While developing a website, we encountered a challenge. We wanted to take information from a web-based form and submit it directly to Google Analytics. However, our host severely limited the ways that we could utilize Google's spreadsheet API with its standard PHP client libraries.

We also wanted something quickly reusable that could scale to other applications.

So, we wrote the enclosed Google Spreadsheet PHP-based form connector. It uses CURL as its primary interfacing point, and can be easily and quickly re-modified to fit other systems.