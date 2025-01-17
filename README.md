# Markdown to HTML Converter

This project provides a set of tools to convert Markdown text into HTML. It includes classes and functions to parse and transform Markdown elements such as bold, italic, code, links, and images into their corresponding HTML representations.

## Files

- `main.sh`: Script to run the main program.
- `test.sh`: Script to run all unit tests.
- `src/copystatic.py`: Contains the function to copy static files recursively.
- `src/gencontent.py`: Contains functions to generate HTML pages from Markdown content.
- `src/htmlnode.py`: Contains classes for HTML nodes (`HTMLNode`, `LeafNode`, `ParentNode`).
- `src/inline_markdown.py`: Functions to parse inline Markdown elements.
- `src/main.py`: Main entry point of the application.
- `src/markdown_blocks.py`: Functions to parse Markdown blocks and convert them to HTML nodes.
- `src/test_gencontent.py`: Unit tests for content generation functions.
- `src/test_htmlnode.py`: Unit tests for HTML node classes.
- `src/test_inline_markdown.py`: Unit tests for inline Markdown parsing functions.
- `src/test_markdown_blocks.py`: Unit tests for Markdown block parsing and conversion functions.
- `src/test_textnode.py`: Unit tests for text node classes and functions.
- `src/textnode.py`: Contains classes for text nodes and functions to convert them to HTML nodes.

## Running the Project

### To run the main program

```sh
./main.sh
```

This will delete the existing `public` directory, copy static files from the `static` directory to the `public` directory, and generate HTML content from the Markdown files in the `content` directory using the `template.html` file.

### To run the tests

```sh
./test.sh
```

This will run all unit tests in the `src` directory.

## License

This project is licensed under the MIT License.
