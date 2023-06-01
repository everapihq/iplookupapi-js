<p align="center">
<img src="https://app.iplookupapi.com/img/logo/iplookupapi.png" width="300"/>
</p>

# iplookupapi-js: IP Geolocation API for JavaScript

This package is a JavaScript wrapper for [iplookupapi.com](https://iplookupapi.com) that aims to make the usage of the API as easy as possible in your project.

## Installation

### npm
```shell
npm install --save @everapi/iplookupapi-js
```
### yarn
```shell
yarn add @everapi/iplookupapi-js
```

## Import

```js
import iplookupapi from '@everapi/iplookupapi-js';
```

or use it directly in a Browser:

```html
<script src="path/to/iplookupapi-js/index.js"></script>
```

## Usage

Initialize the API with your API Key (get one for free at [iplookupapi.com](https://app.iplookupapi.com)):

```js
const iplookupapi = new iplookupapi('YOUR-API-KEY');
```

Afterwards you can make calls to the API like this:

```js
iplookupapi.info({
        ip: '1.1.1.1',
        language: 'de'
    }).then(response => {
        console.log(response);
    });
```

Find out more about our endpoints, parameters and response data structure in the [docs](https://iplookupapi.com/docs)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[docs]: https://iplookupapi.com/docs
[iplookupapi.com]: https://iplookupapi.com
