# Note Taker 


## Description
An application called Note Taker that can be used to write and save notes. This application uses an Express.js back end and will save and retrieve note data from a JSON file

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

## Mock Up

Here's a video showing functionality:

<img src = "utils/mock-up.gif"> 




## Installation
This application is available to use on Heroku! 

<a href='https://pacific-plains-32894.herokuapp.com/'>
<img src='https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white' />
</a>

If you wish to install, read the following guidelines:

_This project requires Node.js_

[How to install](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

After you have installed Node, use the CLI to clone this repository.
```bash
git clone git@github.com:jefid/note-taker
```

Make sure to include the following in your ``.gitignore`` before installing the dependencies!
```sh
node_modules
package-lock.json
.DS_Store
```

Commands to get you started:
```bash
npm install
npm install express
npm install --save nanoid
```

[Express docs](https://expressjs.com/en/4x/api.html) for reference.

Import into your code:

```js
const express = require('express');
const { nanoid } = require('nanoid');
const path = require('path');
```

Start the server from the command line:
```bash
npm start
```

Open your browser to [``http://localhost:3005/``](http://localhost:3005/)

## Credits
To create randomly generated ID's for notes in the database, I utilized
[nano id](https://github.com/ai/nanoid). 

Thank you to GitHub user [ai](https://github.com/ai) for this code!

## Contributing:
Made with ❤️ by Jefferson Quandt

----
## Questions
Feedback and questions are always welcome!
[Github](https://github.com/jefid)
[Email](mailto:jquandt411@gmail.com)