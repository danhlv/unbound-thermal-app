# Unbound Thermal — Web

The [Unbound Thermal](https://danhlv.github.io/unbound-thermal-app/) showcase
site: thermal design, CFD, and data-driven simulation services.

## Stack

- Angular 19 (all content driven from `src/assets/data.min.js`)
- Deployed to GitHub Pages from the `gh-pages` branch

## Develop

```bash
npm install
ng serve            # local dev server
```

## Build & deploy

```bash
ng build --configuration production --base-href /unbound-thermal-app/
# dist/unbound-thermal-app/browser -> gh-pages branch
```

## Credits

Based on [JayantGoel001.github.io](https://github.com/JayantGoel001/JayantGoel001.github.io)
by Jayant Goel, © 2021 Jayant Goel, released under the [MIT License](LICENSE).

## License

Template code is MIT-licensed (see `LICENSE`). Site content and generated
imagery are © 2026 Unbound Thermal.
