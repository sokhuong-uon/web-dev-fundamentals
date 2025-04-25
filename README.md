# Web Development Fundamentals Course

## Lesson: HTML Meta Tags

Meta tags are HTML elements that provide metadata about a webpage. They are placed inside the `<head>` section of an HTML document and are not visible on the page itself. Here's an explanation of common meta tags:

1. **Character Encoding**
   ```html
   <meta charset="UTF-8">
   ```
   - Specifies the character encoding for the webpage
   - UTF-8 is the most common encoding and supports all characters and symbols

2. **Viewport**
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```
   - Controls how the webpage is displayed on mobile devices
   - `width=device-width` makes the page width match the screen width
   - `initial-scale=1.0` sets the initial zoom level

3. **Description**
   ```html
   <meta name="description" content="A simple webpage to demonstrate HTML meta tags">
   ```
   - Provides a brief description of the webpage
   - Often used by search engines in search results

4. **Keywords**
   ```html
   <meta name="keywords" content="HTML, meta tags, web development">
   ```
   - Lists keywords related to the webpage content
   - Less important for SEO than it used to be

5. **Author**
   ```html
   <meta name="author" content="Web Development Fundamentals">
   ```
   - Specifies the author of the webpage

6. **Robots**
   ```html
   <meta name="robots" content="index, follow">
   ```
   - Controls how search engines index and follow links on the page
   - `index` allows the page to be indexed
   - `follow` allows search engines to follow links on the page

7. **X-UA-Compatible**
   ```html
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   ```
   - Tells Internet Explorer to use the latest rendering engine
   - Helps ensure consistent display across different versions of IE

8. **Open Graph Tags (Facebook)**
   ```html
   <meta property="og:title" content="Hi Mom - Web Development Demo">
   <meta property="og:description" content="A simple webpage to demonstrate HTML meta tags">
   <meta property="og:image" content="https://example.com/path/to/image.jpg">
   <meta property="og:image:width" content="1200">
   <meta property="og:image:height" content="630">
   <meta property="og:type" content="website">
   <meta property="og:url" content="https://example.com">
   ```
   - Used for social media sharing on Facebook and other platforms
   - Controls how the page appears when shared
   - `og:title` sets the title for social media shares
   - `og:description` sets the description for social media shares
   - `og:image` specifies the image to display when the page is shared
   - `og:image:width` and `og:image:height` define the image dimensions
   - `og:type` specifies the type of content (website, article, etc.)
   - `og:url` specifies the canonical URL of the page
   - Recommended image size is 1200x630 pixels for optimal display

9. **Twitter Card Tags**
   ```html
   <meta name="twitter:card" content="summary_large_image">
   <meta name="twitter:title" content="Hi Mom - Web Development Demo">
   <meta name="twitter:description" content="A simple webpage to demonstrate HTML meta tags">
   <meta name="twitter:image" content="https://example.com/path/to/image.jpg">
   <meta name="twitter:site" content="@yourtwitterhandle">
   ```
   - Controls how the page appears when shared on Twitter
   - `twitter:card` specifies the type of card (summary, summary_large_image, etc.)
   - `twitter:title` sets the title for Twitter shares
   - `twitter:description` sets the description for Twitter shares
   - `twitter:image` specifies the image to display
   - `twitter:site` links to the website's Twitter account
   - Recommended image size is 1200x630 pixels

10. **Discord Embed Tags**
    ```html
    <meta name="theme-color" content="#5865F2">
    <meta property="discord:embed" content="true">
    <meta property="discord:embed:title" content="Hi Mom - Web Development Demo">
    <meta property="discord:embed:description" content="A simple webpage to demonstrate HTML meta tags">
    <meta property="discord:embed:image" content="https://example.com/path/to/image.jpg">
    ```
    - Controls how links appear when shared in Discord
    - `theme-color` sets the embed color (Discord's brand color is #5865F2)
    - `discord:embed` enables Discord's embed feature
    - `discord:embed:title` sets the title for Discord embeds
    - `discord:embed:description` sets the description
    - `discord:embed:image` specifies the image to display

Meta tags are important for:
- Search Engine Optimization (SEO)
- Social media sharing (Facebook, Twitter, Discord)
- Browser compatibility
- Mobile responsiveness
- Character encoding
- Page description and metadata