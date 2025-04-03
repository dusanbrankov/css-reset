# Custom CSS reset

This CSS reset is for my own usage, it is based on:

**normalize.css**<br />
https://github.com/necolas/normalize.css

**Eric Meyer's CSS Reset**<br />
https://meyerweb.com/eric/tools/css/reset/

**Josh's custom CSS reset**<br />
https://www.joshwcomeau.com/css/custom-css-reset/

## Usage

The CSS reset consists of two files, normalize.css and reset.css. The `css-minify`
package is used to bundle and minify the named files.

```sh
git clone https://github.com/dusanbrankov/css-reset.git
cd css-reset
npm install
npm run minify # save output to reset.min.css
```
