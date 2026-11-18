# Corezanwebsite

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 22.2.3.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
npm run build
```

This creates the production site in `dist/Corezanwebsite/browser/`.

## Deploying to GoDaddy shared hosting

For a domain whose document root is `public_html`:

1. Run `npm run build`.
2. In GoDaddy File Manager, open `public_html`.
3. Upload the **contents** of `dist/Corezanwebsite/browser/` directly into `public_html` (including `index.html`, the JavaScript/CSS bundles, images, and `.htaccess`). Do not upload the `browser` folder itself as a nested folder.
4. If `.htaccess` is not visible in File Manager, enable showing hidden files before uploading it.
5. Visit the domain root and hard-refresh the browser.

The `.htaccess` file sends Angular routes such as `/careers` back to `index.html`; without this Apache rewrite, opening or refreshing a nested route can return a GoDaddy 404. This build is configured for the domain root, not a subdirectory.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
