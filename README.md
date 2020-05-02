# Demo application for nativescript-tailwind

The changes compared to a fresh app created with `vue init`:
 * Installed deps: `npm i postcss postcss-loader tailwindcss nativescript-tailwind --save-dev`
 * Added  `tailwind.config.js` with `npx tailwindcss init` + added the purge option manually
 * Added `postcss.config.js`
 * Edited `app.css` to include tailwind components and utilities. (base is not used in NativeScript, so it's left out from the css)
 * Added 'postcss-loader' to all css rules in `webpack.config.js`
 
To enable purge when building for production, `NODE_ENV` must be set to `production`, for example

```bash
$ NODE_ENV=production tns build android --production --...
```


## Usage

``` bash
# Install dependencies
npm install

# Preview on device
tns preview

# Build, watch for changes and run the application
tns run

# Build, watch for changes and debug the application
tns debug <platform>

# Build for production
tns build <platform> --env.production

```
