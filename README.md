# Eyesore
Theme for Visual studio Code.

Dark UI-elements, light editor area.

## Screenshot
![Screenshot](https://github.com/joonaskoo/eyesore/blob/develop/images/screenshot.png?raw=true)

## Known Issues

### Markdown Preview
Due to a mix of light and dark elements, the font color on markdown preview is really light. To alleviate this, add the following to your user configuration:
``` json
  "markdown.styles": [
    "file:///C:/some/location/eyesoreMarkdown.css"
  ]
```

The file eyesoreMarkdown.css is available [here](https://github.com/joonaskoo/eyesore/blob/develop/themes/eyesoreMarkdown.css).
