# Web Development Fundementals Course

## Basic HTML 5 Document Structure

HTML 5 documents follow a specific structure that defines the foundation of web pages. Here's a breakdown of the essential components:

1. **Document Type Declaration (DOCTYPE)**
   ```html
   <!DOCTYPE html>
   ```
   - This declaration tells the browser that the document is an HTML5 document
   - It must be the first line in any HTML document

2. **HTML Root Element**
   ```html
   <html lang="en">
   ```
   - The `<html>` tag is the root element of an HTML document
   - The `lang` attribute specifies the language of the document

3. **Head Section**
   ```html
   <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Document Title</title>
   </head>
   ```
   - Contains meta-information about the document
   - `<meta charset="UTF-8">` sets the character encoding
   - `<meta name="viewport">` controls how the page is displayed on mobile devices
   - `<title>` defines the title of the document (shown in browser tab)

4. **Body Section**
   ```html
   <body>
     <!-- Content goes here -->
   </body>
   ```
   - Contains the content of the web page
   - All elements like text, images, links, etc. are placed here

## Basic HTML 5 Template
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

This structure provides the foundation for creating web pages and ensures proper rendering across different browsers and devices.