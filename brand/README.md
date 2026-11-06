# Quire brand files

The Quire name, wordmark and "Q" mark are trademarks of YorvoLabs. Quire's code is open source under the MIT license, but the license doesn't cover the name or the logos (see [Using the name and logos](#using-the-name-and-logos)).

## Files

| File | Use it for |
|------|------------|
| `quire-wordmark-navy.png` | The "Quire" wordmark on light backgrounds (transparent, 720 × 246) |
| `quire-wordmark-white.png` | The wordmark on dark backgrounds (transparent, 720 × 249) |
| `quire-mark-navy.png` | The "Q" mark on light backgrounds, where the wordmark doesn't fit, e.g. as an icon (transparent, 256 px) |
| `quire-mark-white.png` | The "Q" mark on dark backgrounds (transparent, 256 px) |
| `quire-avatar.png` | Profile pictures, e.g. of the GitHub organisation (white "Q" on navy, 500 × 500) |
| `quire-social-preview.png` | The image shown when a repository is shared, e.g. on social networks (1280 × 640) |

In a README, show the wordmark that suits the reader's colour scheme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/quirecms/.github/main/brand/quire-wordmark-white.png">
  <img src="https://raw.githubusercontent.com/quirecms/.github/main/brand/quire-wordmark-navy.png" alt="Quire" width="320">
</picture>
```

## Colours

| Colour | Hex | Use |
|--------|-----|-----|
| Navy | `#1c184b` | The letters, and backgrounds behind the white versions |
| Orange | `#f9991b` | The folded corner of the "Q" only |
| White | `#ffffff` | The letters on navy |

## Using the name and logos

You may use the name "Quire" and the logos to refer to the project, e.g. in an article, a talk, or to say that your extension or theme works with Quire, as long as it's clear that you aren't YorvoLabs and that YorvoLabs doesn't endorse your work.

Please don't:

- change the logos: their colours, proportions or the folded corner, or add effects;
- use them in a way that suggests your product, company or event is Quire's or endorsed by YorvoLabs;
- use "Quire" as the first word of a product or package name. "Reviews for Quire" is fine, "Quire Reviews" isn't. Packages use their own vendor name, e.g. `acme/quire-reviews`.

For anything else, write to [hello@quirecms.com](mailto:hello@quirecms.com), or open an issue in [quirecms/framework](https://github.com/quirecms/framework/issues).
