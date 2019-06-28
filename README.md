# roboto-fontface-material
Font library for local install of Roboto variants used by Angular Material.

Only the woff and woff2 versions are included since they are sufficient to support every modern browser.
Also, only the fontweights and styling used by Material is included. This takes us down to three fonts.

## Installation

```
npm install roboto-fontface-material
```

## Usage
In your main angular project, add this line to the scripts section in `angular.json`:
```json
"node_modules/roboto-fontface-material/fonts/roboto-fontface-material.css"
```
This ensures that the font files are included in your assets when building your application, and
Material will automatically use your local versions.

## License notes
The MIT license applies to this compilation of the Roboto fonts for Angular Material.
The fonts themselves are created by Christian Robertson and are released under the Apache license.
(Google's font page)[https://fonts.google.com/specimen/Roboto]
(Roboto font license)[http://www.apache.org/licenses/LICENSE-2.0]