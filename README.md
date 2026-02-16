# css-background-size

Functional CSS for background-size

## Filesize

| File | Size |
|------|------|
| `dist/background-size.css` | 1445 bytes |
| `dist/background-size.min.css` | 1053 bytes (236 Gzipped) |

## Install

```sh
npm install css-background-size
```

## Usage

### Import

```css
@import "css-background-size";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-background-size/dist/background-size.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-background-size/dist/background-size.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.bg-cover` | `background-size: cover;` |
| `.bg-contain` | `background-size: contain;` |
| `.bg-quarter` | `background-size: 25%;` |
| `.bg-half` | `background-size: 50%;` |
| `.bg-three-quarters` | `background-size: 75%;` |
| `.bg-full` | `background-size: 100%;` |
| `.bg-auto` | `background-size: auto;` |
| `.bg-cover-s` | `background-size: cover;` |
| `.bg-contain-s` | `background-size: contain;` |
| `.bg-quarter-s` | `background-size: 25%;` |
| `.bg-half-s` | `background-size: 50%;` |
| `.bg-three-quarters-s` | `background-size: 75%;` |
| `.bg-full-s` | `background-size: 100%;` |
| `.bg-auto-s` | `background-size: auto;` |
| `.bg-cover-m` | `background-size: cover;` |
| `.bg-contain-m` | `background-size: contain;` |
| `.bg-quarter-m` | `background-size: 25%;` |
| `.bg-half-m` | `background-size: 50%;` |
| `.bg-three-quarters-m` | `background-size: 75%;` |
| `.bg-full-m` | `background-size: 100%;` |
| `.bg-auto-m` | `background-size: auto;` |
| `.bg-cover-l` | `background-size: cover;` |
| `.bg-contain-l` | `background-size: contain;` |
| `.bg-quarter-l` | `background-size: 25%;` |
| `.bg-half-l` | `background-size: 50%;` |
| `.bg-three-quarters-l` | `background-size: 75%;` |
| `.bg-full-l` | `background-size: 100%;` |
| `.bg-auto-l` | `background-size: auto;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.bg-cover-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/background-size.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/background-size.css` — formatted
- `dist/background-size.min.css` — minified

## License

MIT
