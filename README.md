# Translation API Documentation (Node.js)

## Overview

The Translation API allows you to translate text from one language to another using a simple HTTP POST request. It utilizes the Express framework for handling web requests and a text translation library for performing translations.

## Base URL

The base URL for the API is [https://startupproject-391507.uc.r.appspot.com](https://startupproject-391507.uc.r.appspot.com/).

## Translate Endpoint

### Endpoint

- **URL:** `/translate`
- **Method:** `POST`

### Request

#### Input

The endpoint expects a JSON payload with the following parameters:

- **text (string, required):** The text to be translated.
- **target_language (string, required):** The language code of the target language.

Example Request:

```json
{
  "text": "Hello, how are you?",
  "target_language": "es"
}
