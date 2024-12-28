# Structured Data AKA JSON+LD

Structured data is a way to provide more information to search engines about your content. It helps search engines understand the content and improve the page's ranking.

## Issue #1: No structured data
In T3leem, we noticed that many pages don't have structured data, it's an easy fix and will reflect positively on the page's SEO.

## How to Fix It

1. Add structured data to the all public pages.
2. Test your pages with Google Structured Data Testing Tool: https://developers.google.com/search/docs/appearance/structured-data

## Example code
```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Article headline",
  "datePublished": "2024-01-01"
}
```

## Notes
- The structured data should be in the `<head>` tag.
- The structured data should be dynamic and unique to the page content.

## Resources
- https://developers.google.com/search/docs/appearance/structured-data
- https://schema.org/
- https://validator.schema.org/
