<div align="center">

[![Thiradus Dark Banner](https://raw.githubusercontent.com/Thiradus/Branding/master/Graphics/Banner/Banner-Dark.png)](https://thiradus.com/)

<h2>CORS Middleware</h2>

[![CodeFactor](https://www.codefactor.io/repository/github/thiradus/cors-middleware/badge)](https://www.codefactor.io/repository/github/thiradus/cors-middleware) [![Depfu](https://badges.depfu.com/badges/20285344da99d629b259c64b9591d1cd/overview.svg)](https://depfu.com/github/Thiradus/cors-middleware?project_id=11307) ![Downloads](https://img.shields.io/npm/dt/thiradus-cors-middleware?style=flat) ![MIT License](https://img.shields.io/github/license/Thiradus/cors-middleware?style=flat)

</div>

## Overview

A simplistic yet effective Cross-Origin Resource Sharing [Express.js](https://expressjs.com/) Middleware.

## Installation

```Bash
npm install thiradus-cors-middleware --save
```

## Usage

### Example

```JavaScript
const cors = require('thiradus-cors-middleware');
const express = require('express');

const app = express();

app.use(cors);
```

## License

This repository is licensed under the [MIT](./LICENSE.md) License &copy; 2015-2021 [Thiradus](https://github.com/Thiradus/)
