# Hugo Theme TH

A minimalist Hugo theme for Thomas Hühn's blogs with multi-language support.

## Features

- Clean, minimalist design
- Multi-language support (English/German)
- Language-aware date formatting
- Dark mode support via CSS `prefers-color-scheme`
- Responsive design
- RSS feed support
- Tag system
- Favorite posts highlighting

## Installation

### As a Git Submodule

```bash
git submodule add https://github.com/th/hugo-theme-th.git themes/hugo-theme-th
```

### As a Hugo Module

```bash
hugo mod get github.com/th/hugo-theme-th
```

## Configuration

Add to your `config.yaml`:

```yaml
theme: hugo-theme-th
```

The theme automatically detects the language from your site's `languageCode` setting and formats dates accordingly:

- `en`: English date format (January 2, 2006)
- `de`: German date format (2. Januar 2006)

## Supported Languages

- English (`en`)
- German (`de`)

## License

All rights reserved.