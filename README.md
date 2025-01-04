# Cat Photo App

Welcome to the **Cat Photo App**, a simple HTML project showcasing adorable cat photos, fun lists about cats, and a form to submit cat-related information. This app is perfect for practicing basic HTML structure and form elements.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

## Overview

The Cat Photo App is a static HTML project designed to:
- Display cute cat photos and captions.
- Share interesting lists about things cats love and hate.
- Include a form for users to submit cat-related information.

## Features

- **Cat Photos**: A gallery of cat images and external links to more cat content.
- **Lists**:
  - Things cats love.
  - Things cats hate.
- **Interactive Form**:
  - Radio buttons to select if a cat is indoor or outdoor.
  - Checkboxes for cat personality traits.
  - Text input for cat photo URL submission.

## Technologies Used

- **HTML5**: The project is built entirely with HTML5, demonstrating semantic elements, links, forms, and lists.

## Getting Started

To view the Cat Photo App:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/cat-photo-app.git
    ```
2. Open the `index.html` file in your web browser.

That's it! No additional setup is required.

## Usage

Explore the following sections in the app:

1. **Cat Photos**: View a cute photo and follow links for more cat content.
2. **Cat Lists**: Learn about what cats love and hate.
3. **Cat Form**: Fill out and submit the form to describe your cat.

## Example Code

Here is an example of the Cat Form:

```html
<form action="https://freecatphotoapp.com/submit-cat-photo">
  <fieldset>
    <legend>Is your cat an indoor or outdoor cat?</legend>
    <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
    <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
  </fieldset>
  <fieldset>
    <legend>What's your cat's personality?</legend>
    <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
    <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
    <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
  </fieldset>
  <input type="text" name="catphotourl" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
```

## License

This project is a **No Copyright** project. Feel free to use, share, and modify it as needed.
