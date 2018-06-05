# Object-fit - TailwindCSS Plugin

This plugin generates classes for object-fit image properties.

## Installation

Pull it in through npm or yarn:

```bash
npm install tailwindcss-object-fit
```

```bash
yarn add tailwindcss-object-fit
```

## Usage

Just add it to the plugins array of your Tailwind config.

```js
plugins: [
  // Other plugins
  require('tailwindcss-object-fit')(['responsive']),
],
```

By default the plugin generates the following classes:

```css
.object-contain: { objectFit: 'contain' }
.object-cover: { objectFit: 'cover' }
.object-fill: { objectFit: 'fill' }
.object-none: { objectFit: 'none' }
.object-scale: { objectFit: 'scale-down' }
```

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
