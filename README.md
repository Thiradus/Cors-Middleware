
# thiradus-cors-middleware
![Downloads](https://img.shields.io/npm/dt/thiradus-cors-middleware?style=flat-square)![MIT License](https://img.shields.io/github/license/Thiradus/cors-middleware?style=flat-square)[![Depfu](https://badges.depfu.com/badges/20285344da99d629b259c64b9591d1cd/overview.svg)](https://depfu.com/github/Thiradus/cors-middleware?project_id=11307)
## Overview

A simplistic yet effective Cross origin resource sharing [Express.js](https://expressjs.com/) middleware.

## Installation

```Bash
npm install thiradus-cors-middleware --save
```

## Usage

### Example

```JavaScript
const cors = require('thiradus-cors-middleware')
const express = require('express');

const app = express();

app.use(cors);
```

## License

This project is licensed under the [MIT](./LICENSE.md) License &copy; 2015-2020 [Thiradus](https://github.com/Thiradus/)
