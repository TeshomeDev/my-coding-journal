# HTML Basics — Important Concepts

- **HTML** = HyperText Markup Language, defines the **structure** of web pages.
- **Document structure**: 
  - `<!DOCTYPE html>` → tells browser the HTML version.
  - `<html>` → root element of the page.
  - `<head>` → contains metadata like `<title>`, `<meta charset="UTF-8">`, `<meta name="viewport">`.
  - `<body>` → contains visible content like headings (`<h1>`), paragraphs (`<p>`), images, links.
- **Headings**: `<h1>`–`<h6>` define content hierarchy.
- **Paragraphs**: `<p>` wrap text content.
- **Important:** `<meta charset="UTF-8">` ensures proper character display.
- **Important:** `<meta name="viewport" content="width=device-width, initial-scale=1.0">` makes page mobile-friendly.

---

# HTML Basics

`<!DOCTYPE html>`
- Declares the HTML version (HTML5).
- Must be the first line in the HTML document.
- Ensures brower renders the page correctly.

`<html>`
- Root element of the HTML page.
- All content must be inside <html>...</html>.
- Attribute: lang="en" is used to specify the page language and for accessibility.

`<head>`
- Contains meta-information about the page.
- Elements nested in the head are:
  - `<title>` → sets the tab name.
  - `<meta>` → where information of the page is kept.
    - **Essential meta tag attributes**
      - (charset):
       ensures texts on the page are displayed correctly on different browsers and environments.
      **Syntax:** `<meta charset="UTF-8">`
      - (viewport): makes website mobile friendly and responsive.
      **Syntax:** `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
      - (description): gives a brief summary of a webpage which is shown in search engine results.
      **Syntax:** `<meta name="description" content="A brief summary of a webpage">`
    
  - `<link>` and `<script>` → connect external files.

**Note:** all contents in head aren't visible on the web page but vital for browsers, search engines and other services as accessibility.

`<body>`
- Contains all content visible on the page.

---

# Headings 
`<h1>...<h6>`
- They are essential for:
  - **SEO (Search Engine Optimization):**
    Search engines use headings to understand page structure and rank content properly.

  - **Accessibility:**
    Screen readers use headings to help visually impaired users navigate your page easily.

  - **Readability:**
    Headings make pages easier for humans to scan and understand quickly.


