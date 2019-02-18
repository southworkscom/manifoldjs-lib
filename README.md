# PWABuilder-Lib

The PWABuilder-Lib contains the core modules required by [PWA Builder](https://github.com/pwa-builder/PWABuilder-CLI), a tool for creating hosted web applications based on a [W3C Web App manifest](http://www.w3.org/TR/appmanifest/).
With this library you can get the manifest from a site or generate it if the site hasn't got one. Also, it can generate the missing images in the manifest and get the service worker information, among another things.

## Installation

```
npm install pwabuilder-lib
```
In node.js:

```
var lib = require('pwabuilder-lib')
```

## Documentation

Manifest Tools

| Method                       | Description                                                                 | 
| ---------------------------- |:-------------:                                                              |
| getManifestFromSite          | Retrieves a site's manifest. If the site hasn't got one it would create it. |
| getManifestFromFile          | Retrieves a manifest from a local file.                                     | 
| writeToFile                  | Saves a manifest to a local file.                                           | 
| fetchManifestUrlFromSite     | Gets the manifest's URL from a site.                                        |
| downloadManifestFromUrl      | Downloads a site's manifest information.                                    |
| generateImagesForManifest    | Generates the missing images for the manifest.                              |
| listAvailableManifestFormats | Gets the availables formats for the manifest.                               |


To get started, visit our [wiki](https://github.com/manifoldjs/ManifoldJS/wiki).

## License

> pwabuilder-lib

> Copyright (c) Microsoft Corporation

> All rights reserved.

> MIT License

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ""Software""), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.