# URL Shortener App

## Overview

The URL Shortener App is a web service that converts long website addresses into shorter, more manageable links. This makes URLs easier to share and remember.

## Features

- **URL Shortening**: Users can input a lengthy URL, and the app will generate a shorter version.

- **Custom Aliases**: Users can provide a custom alias for their shortened URL, or let the app generate a random one.

- **Redirection**: Accessing the short URL redirects the user to the original long URL.

- **404 Error Handling**: If a non-existent short URL is accessed, a 404 error page is displayed.

- **URL Management**: A table on the main page lists all previously shortened URLs for easy reference.

## Short URL Format

The short URLs are structured as follows:

```

http://localhost:3000/{alias}

```


## Usage

1\. **Submit URL**: Enter a long URL and optionally an alias in the provided form.

2\. **Generate Short URL**: Submit the form to create a shortened URL.

3\. **Access Short URL**: Use the short URL to be redirected to the original long URL.

4\. **Error Handling**: Encounter a 404 error if a short URL does not exist in the database.
