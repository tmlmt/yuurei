# Yuurei

Fork of [Edge](https://github.com/TryGhost/Edge), a visually aesthetic [Ghost](https://github.com/TryGhost/Ghost) theme designed for creative professionals. _Yuurei_ means _Ghost_ in Japanese :)

# Specific features compared to Edge

- LinkedIn icon in the Header, available as a custom setting in Ghost admin

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/edge.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Copyright & License

Copyright (c) 2013-2023 Ghost Foundation  
Copyright (c) 2023 Thomas Lamant  
Released under the [MIT license](LICENSE)