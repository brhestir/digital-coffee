# digital-coffee

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Links](#links)
- [Credits](#credits)
- [Contributors](#contributors)
- [Contributions](#contributions)
- [Questions](#questions)
- [License](#license)

## Description

In this first group project of the bootcamp, we built "Digital Coffee" utilizing several different APIs to generate user's choices of:

- Quotes
- Background Images
- Weather Information

## Installation

```bash
$ cd ~
$ git clone https://github.com/brhestir/digital-coffee.git
$ npm install
```

## Usage

```bash
npm start
```

## Links

- [Deployed @ GitHub Pages](https://brhestir.github.io/digital-coffee/)
- [GitHub Repository](https://github.com/brhestir/digital-coffee)

## Contributors

- [Sungpil An](ansungpil1@gmail.com)
- [Derrick Hardison](derricklhardison@gmail.com)
- [Brian Hestir](brhestir@gmail.com)
- [Tony Schwebach](tony.schwebach.developer@gmail.com)

## Credits

- [Boostrap](https://getbootstrap.com/)
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Moment.JS](https://momentjs.com/)
- [JQuery](https://jquery.com/)
- [Open Weather API](https://api.openweathermap.org/data/2.5/weather)
- [Pexel API](https://api.pexels.com/v1/search?query)
- [icanhazdadjoke API](https://icanhazdadjoke.com)
- [Inspirational quote API](https://type.fit/api/quotes)
- [Taylor Swift Quotes API](https://api.taylor.rest)
- [Ron Swanson Quotes API](https://ron-swanson-quotes.herokuapp.com/v2/quotes)
- [Chuck Norris Jokes API](https://api.chucknorris.io/jokes/random)

## Features

- [Toggler](#toggler)
- [Highlights](#highlights)

### Toggler

---

Here is the Navbar:

![navbar](./assets/images/navbar.jpg)

On the right corner of Navbar, you will see a "settings button", which is the choice toggler.

![toggler](./assets/images/toggler.jpg)

Once you click the toggler icon, it will provide you with three different inputs to choose from:

- Quote Theme
- Photo Theme
- Type your city name (To find the current weather for your desired location)

![selector](./assets/images/selectors.jpg)

### Highlights

---

We display the time using moment.js:
![timer](./assets/images/time.jpg)

#### Quote / Photo Theme Selector & Weather Search - User can select his or her choices of

"Quote Theme"

![quote](./assets/images/quote.jpg)

"Photo Theme"

![photo](./assets/images/photo.jpg)

"Weather for A Chosen City."

![weather](./assets/images/winput2.jpg)

A user will receive these results according to the selected choices:

- Quote
- Background Image
- Weather Information (After your search, click "Undo" button to refresh)

![quoteresult](./assets/images/result.jpg)

## License

Licensed under the [MIT License](LICENSE.md):

Copyright (c) [2020] [Sungpil An, Derrick Hardison, Brian Hestir and Tony Schwebach]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
