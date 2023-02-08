# Web Optimizer

This extension is for Web developers who wants to increase the speed of their website. It contains some HTML snippets for now. I will provide more features in the future.

> This extension is still in progress.  [Let me know](https://github.com/doggy8088/web-optimizer/issues) if you have any suggestion! Thanks!

## Features

* HTML snippets

## HTML Snippets

Head

| Prefix                   | Description                                                                                       |
| ------------------------ | ------------------------------------------------------------------------------------------------- |
| `link-preconnect`        | Specifies that the user agent should preemptively connect to the target resource's origin.        |
| `link-preconnect-common` | Specifies that the user agent should preemptively connect to the common target resource's origin. |

SEO

| Prefix         | Description         |
| -------------- | ------------------- |
| `meta:seo`     | SEO Meta Tags       |
| `meta:og`      | OpenGraph Meta Tags |
| `meta:twitter` | Twitter Meta Tags   |

Image

| Prefix               | Description                                                  |
| -------------------- | ------------------------------------------------------------ |
| `img-srcset`         | The `<img>` HTML element with `srcset`                       |
| `img-srcset-sizes`   | The `<img>` HTML element with `srcset` and `sizes`           |
| `picture-type`       | The `<picture>` and `<source>` HTML element                  |
| `picture-type-media` | The `<picture>` and `<source>` HTML element with Media Query |
| `picture-srcset-2x`  | The `<picture>` and `<source>` HTML element with Media Query |

## Contributing

If you have any idea, please feel free to send PRs to me or simply [drop me a note](https://github.com/doggy8088/web-optimizer/issues)! 😊

## Build & Test

```sh
npm run build
```

Just hit `F5` in the Visual Studio Code.

**Enjoy!**
