# HTML Structure

The HTML structure is often overlooked, yet it's crucial for SEO. A well-structured HTML page helps search engines understand the content and improve the page's ranking.

Generally speaking, each page should have at least one `<h1>` tag, and it should be unique to the page and contains the targeted keyword.

## Issue #1: No `<h1>` tag
In T3leem, we noticed that many pages don't have an `<h1>` tag, this is a big issue and needs to be fixed ASAP.

## How to Fix It

1. Add an `<h1>` tag to the page.
2. Make sure the `<h1>` tag is unique to the page and contains the targeted keyword.
3. Make sure there is only one `<h1>` tag per page.

---

## Issue #2: Invalid HTML headers hierarchy
The HTML headers hierarchy is important for SEO, as it helps search engines understand the content and improve the page's ranking.

The headers hierarchy should be as follows:

- `<h1>` Page title, should be unique to the page and contains the targeted keyword.
- `<h2>` Section title, should be unique to the page and contains the targeted keyword.
- `<h3>` Sub-section title, should be unique to the page and contains the targeted keyword.
- `<h4>` Sub-sub-section title, should be unique to the page and contains the targeted keyword.
- `<h5>` Sub-sub-sub-section title, should be unique to the page and contains the targeted keyword.
- `<h6>` Sub-sub-sub-sub-section title, should be unique to the page and contains the targeted keyword.

## How to Fix It
Ensure the headers hierarchy is correct based on the page content, header levels should not compete with each other and should be used in the correct order.

---

## Issue #3: Missing meta tags
The meta tags are important for SEO, as they help search engines understand the content and improve the page's ranking and also improves the page google search snippet.


## How to Fix It
Replace the placeholders with the correct values. make sure the values are dynamic and avoid duplication as much as possible.

**Note:** The meta tags should be in the `<head>` tag.

The meta tags should be as follows:
```html
    <meta name="description" content="{{Dynamic description of the page (Avoid duplication as much as possible)}}">
    <meta name="keywords" content="{{Dynamic keywords of the page (Avoid duplication as much as possible)}}">
    <link rel="canonical" href="{{Current page URL}}">
    <title>{{Page Title (include the targeted keyword)}}</title>
    <meta name="application-name" content="{{Application Name}}">
    <meta name="msapplication-TileImage" content="{{Application Icon URL}}">
    <meta name="msapplication-TileColor" content="{{Application Tile Color (HEX Code)}}">
    <link rel="icon" type="image/x-icon" href="{{Application Icon URL}}">
```

___

## Issue #4: Missing Open Graph meta tags
The Open Graph meta tags are important for SEO, as they help search engines understand the content and improve the page's ranking and also improves the page google search snippet.

## How to Fix It
Replace the placeholders with the correct values. make sure the values are dynamic and avoid duplication as much as possible.

The Open Graph meta tags are mostly used for social media sharing, but they can also help with SEO.

**Note:** The meta tags should be in the `<head>` tag.

The Open Graph meta tags should be as follows:
```html
    <meta property="og:title" content="{{Page Title (include the targeted keyword)}}">
    <meta property="og:type" content="website">
    <meta property="og:url" content="{{Current page URL}}">
    <meta property="og:image" content="{{Application Image URL}}">
    <meta property="og:description" content="{{Dynamic description of the page (Avoid duplication as much as possible)}}">
    <meta property="og:site_name" content="{{Application Name}}">
```

___

## Issue #5: Missing Twitter meta tags
The Twitter meta tags are important for SEO, as they help search engines understand the content and improve the page's ranking and also improves the page google search snippet.

## How to Fix It
Replace the placeholders with the correct values. make sure the values are dynamic and avoid duplication as much as possible.

It's unclear if the rebranding to "X" has changed the Twitter meta tags importance yet, but it's a good practice to add them.

**Note:** The meta tags should be in the `<head>` tag.

The Twitter meta tags should be as follows:
```html
    <meta name="twitter:card" content="{{Dynamic description of the page (Avoid duplication as much as possible)}}">
    <meta name="twitter:site" content="{{Application Name}}">
    <meta name="twitter:creator" content="@naqrahofficial">
    <meta name="twitter:image" content="{{Application Icon URL}}">
    <meta name="twitter:title" content="{{Page Title (include the targeted keyword)}}" />
    <meta name="twitter:description" content="{{Dynamic description of the page (Avoid duplication as much as possible)}}">
```

---

## Issue #6: Missing alt attributes
The alt attributes are important for SEO, as they help search engines understand the images content.

## How to Fix It
1. Make sure all images have alt attributes.
2. Make sure the alt attributes are descriptive.
3. Make the alt attributes unique to each image language.

## Example
```html
    <img src="image.jpg" alt="Description of the image">
```

**Note:** The alt attributes should be in the `<head>` tag.

## Resources
- https://ogp.me/
- https://www.opengraph.xyz