# JupyterToPDF

`JupyterToPDF` is a Python package designed to simplify the process of converting Jupyter notebooks (`.ipynb` files) into PDF documents. This tool aims to provide an easy and automated way for users to generate PDFs from their Jupyter notebooks, either saving them in the same directory as the notebook or in a specified output directory.

## Features

- Convert Jupyter notebooks to PDF with a single function call.
- Option to specify the output directory for the generated PDF.
- Simple and easy to use, integrating seamlessly with your Jupyter workflow.

## Installation

Install `JupyterToPDF` using pip:

```bash
pip install JupyterToPDF
```

## Dependencies

- `pdfkit`: Used for the conversion process.
- `wkhtmltopdf`: A command-line tool required by `pdfkit` for converting HTML to PDF. Make sure it's installed on your system. It can be downloaded from [wkhtmltopdf.org](https://wkhtmltopdf.org).


## Usage

Here's how to use `JupyterToPDF`:

```python
from JupyterToPDF import convert_notebook_to_pdf
```

# Convert a notebook to PDF and save in a specific output folder
convert_notebook_to_pdf('path/to/notebook.ipynb', 'path/to/output/folder')

# Save the PDF in the same folder as the notebook
convert_notebook_to_pdf('path/to/notebook.ipynb')


## License

JupyterToPDF is open-source software licensed under the [MIT License](https://opensource.org/licenses/MIT).


## Author

Nayeem Islam

- LinkedIn: [nayeemislam60053](https://linkedin.com/in/nayeemislam60053)
- GitHub: [nomannayeem](https://github.com/nomannayeem)


## Contributing

Contributions to `JupyterToPDF` are welcome! If you're interested in helping to improve the project, please read the contributing guidelines to get started.

- Ensure your code adheres to the project's standards.
- Include tests for new functionality.
- Document any changes or improvements.
