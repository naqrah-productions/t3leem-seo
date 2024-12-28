# General

This section contains general recommendations about the website, they don't fit in any other category.

## Sitemaps

Sitemaps are `xml` files that help search engines list the website pages without having to crawl each and every page, the best practice is to create them dynamically using a backend service.

## Robots.txt

The `robots.txt` file is used to tell search engines which pages to crawl and which to ignore.

## Redirects

- Make sure to use 301 redirects when the page is permanently moved.
- Make sure to use only www or non-www versions of the website. redirect the other version to the correct one using 301 redirects.
- Make sure to enforce SSL on the website.
- Make sure to minimize the number of inline styling and scripts.
- Avoid having any JS errors on the page even if it's not blocking the users.
