# atgtask

This project is a FastAPI application that can be used to extract text from images. The application is built using the fastapi, jinja2, shutil, os, and ocr libraries. The application has two endpoints: / and /extract_text. The / endpoint is the home page of the application, which renders a templated HTML page that allows users to upload images. The /extract_text endpoint is used to extract text from images. When a user uploads an image to this endpoint, the application saves the image to a temporary file and then uses the ocr library to extract the text from the image. The extracted text is then returned to the user.

The application can be used to extract text from images in a variety of formats, including JPEG, PNG, and GIF. The extracted text can then be used for a variety of purposes, such as data entry, translation, and search.

The project is easy to use, powerful, and flexible. It can be used by anyone with a web browser and can extract text from a variety of images.
