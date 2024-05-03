# Jate Text Editor

![Node.js](https://camo.githubusercontent.com/85cba226a1290d078f1a437aa87cb872a5bdb30037fa96b8afcddf163cd5b328/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d4e6f64652e6a7326636f6c6f723d333339393333266c6f676f3d4e6f64652e6a73266c6f676f436f6c6f723d464646464646266c6162656c3d)
![Webpack](https://camo.githubusercontent.com/f3944c177a39c401f0a1747b4e37256098429039dc84610b542937b768e93d92/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d5765627061636b26636f6c6f723d323232323232266c6f676f3d5765627061636b266c6f676f436f6c6f723d384444364639266c6162656c3d)
![JavaScript](https://camo.githubusercontent.com/dc9450fb8d40c110f245200f5dadff7551cb6cff83250579789bb997dacf987d/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d4a61766153637269707426636f6c6f723d323232323232266c6f676f3d4a617661536372697074266c6f676f436f6c6f723d463744463145266c6162656c3d)

## Built With

- Node.js
- Webpack
- JavaScript

## Description

Jate or just another text editor is a a progressive web application. This application uses webpack to add necessary plugins including css-loader and babel to be able to run newer css and javascript on older devices. It also utilizes asset caching with the service worker giving the ability to use the application without internet connection. For persisting data, it uses IndexedDB. The manifest plugin in the webpack along with the installation event handlers allow you to distribute this application to each user's personal devices that can be used without internet connection.

## Table of Contents

- [Jate Text Editor](#jate-text-editor)
  - [Built With](#built-with)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation(Locally)](#installationlocally)
  - [Usage](#usage)
  - [Visuals](#visuals)
  - [Tests](#tests)
  - [Credits](#credits)
  - [References](#references)
  - [License](#license)
  - [Future Development](#future-development)
  - [Contributing](#contributing)
  - [Badges](#badges)
  - [Questions](#questions)

## Installation(Locally)

- Fork the repo to make a copy.
- Next, clone the project using `git clone https://github.com/ianahart/jate-text-editor.git`.
- In the root of the directory run `npm install` to install the dependencies for the client and the server.
- After the dependencies have been installed run the command `npm run start` to startup the application.
- You will be able to visit the application at `http://localhost:8080/` specifed by webpack.

## Usage

To use the application click inside the editor and start writing some JavaScript! :)

## Visuals

Visit Live application [here](jate-text-editor-34b2.onrender.com/)

<img width="650" alt="jate" src="https://github.com/ianahart/jate-text-editor/assets/29121238/aea24cd2-ed79-47de-ba69-8a6e39f30621">


## Tests

N/A

## Credits

Most of the boilerplate for this project was provided by edX bootcamps.

## References

- [Idb npm package](https://www.npmjs.com/package/idb)
- [Workbox](https://developer.chrome.com/docs/workbox/caching-resources-during-runtime)

## License

This project is covered under MIT License

<details>
  <summary>
    License Text
  </summary>

```

Copyright (c) 2024  Ian Hart

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

```

</details>

## Future Development

As of now I have no plans to develop this application any further. However, this code base can be used as a starting point for future of development of a text editor.

## Contributing

No contributions are being accepted at this time.

## Badges

[![GitHub license](https://img.shields.io/github/license/ianahart/jate-text-editor)](https://github.com/ianahart/jate-text-editor/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/ianahart/jate-text-editor)](https://github.com/ianahart/jate-text-editor/issues)
[![GitHub stars](https://img.shields.io/github/stars/ianahart/jate-text-editor)](https://github.com/ianahart/jate-text-editor/stargazers)

## Questions

- Get in touch with me through [email](mailto:ianalexhart@gmail.com).
- Check out my GitHub [profile](https://github.com/ianahart).
