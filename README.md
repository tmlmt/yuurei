# Yuurei

Fork of [Edge](https://github.com/TryGhost/Edge), a visually aesthetic [Ghost](https://github.com/TryGhost/Ghost) theme designed for creative professionals. _Yuurei_ means _Ghost_ in Japanese :)

![image](https://user-images.githubusercontent.com/10244927/216927801-12cfac1b-185f-4c62-80cc-0b9a4922018d.png)

# Specific features compared to Edge

## Fixes

- \[Mobile\] Compact footer
- \[Mobile\] Do not generate a `<nav>` element when no secondary navigation items are set

## Controlled by custom settings in Ghost admin

- LinkedIn icon in the Header linking to LinkedIn profile
- Possibility to select the width of the feature image in posts: wide or regular

## Hard-coded stylistic choices

- Very short line below title, no bottom margin: the first h2 becomes a sub-title
- Gallery width constrained to main grid width
- Max 3 grid items in the width
- Justified paragraph text

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
