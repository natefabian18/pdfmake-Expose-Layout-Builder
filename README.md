# PDFMake forked from
https://github.com/natefabian18/pdfmake-Expose-Layout-Builder/tree/0.2

This is a small fork of PDFmake to make sure that the builder can be accessed to get the size params of your PDF

creates `ExposeLayoutBuilder()` under the PDF printer that returns the internal layout builder with all its fixings.
Is a copy of `createPdfKitDocument()` up until it starts to create the pages.
