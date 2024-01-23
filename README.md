# Doxygen dark theme

## Usage

Modify your doxygen input file, usually named `Doxyfile`, with the following options:

```
# Add css files to extra stylesheet

HTML_EXTRA_STYLESHEET  = "css/style.css" \
                         "css/dark_style.css"
```

Custom made HTML header and footer by enabling this feature with:

```
HTML_HEADER            = "header.html"

HTML_FOOTER            = "footer.html"
```

