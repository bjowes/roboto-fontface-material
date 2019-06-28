# roboto-fontface-material
Font library for local install of Roboto variants used by Angular Material.

Only the woff and woff2 versions are included since they are sufficient to support every modern browser.
Also, only the fontweights and styling used by Material is included. This takes us down to three fonts.

## Usage
In your main css/scss file in your project, add this line:
```css
@import '~roboto-fontface-material/fonts/roboto-fontface-material.css';
```
This ensures that the font files are included in your assets when building your application.

## License notes
The MIT license applies to this compilation of the Roboto fonts for Material.
The fonts themselves are created by Christian Robertson and are released under the Apache license.
(Google's font page)[https://fonts.google.com/specimen/Roboto]
(Font license)[http://www.apache.org/licenses/LICENSE-2.0]