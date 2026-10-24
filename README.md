# Convert PowerPoint to PDF

A local web page that accepts one `.ppt` or `.pptx` upload and converts it to PDF with LibreOffice. Any other type gets `Only PowerPoint files are allowed!` The upload limit is 50 MB. The server starts at port 3000 and moves to the next free port if 3000 is taken.

## Convert a file

Install [LibreOffice](https://www.libreoffice.org/download/download/), then:

```bash
npm install
npm start
```

Open the URL the server prints (it begins at `http://localhost:3000`) and upload the presentation.

## License

[MIT](LICENSE)
