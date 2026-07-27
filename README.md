# WIDTH ART DIRECTION TEST

<picture>
  <source media="(max-width: 500px)" srcset="assets/narrow.svg">
  <img alt="art direction test" src="assets/wide.svg" width="800">
</picture>

## combined width + color-scheme

<picture>
  <source media="(max-width: 500px) and (prefers-color-scheme: dark)" srcset="assets/narrow.svg">
  <source media="(max-width: 500px)" srcset="assets/narrow.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/wide.svg">
  <img alt="combo test" src="assets/wide.svg" width="800">
</picture>
