# Zod Snippets

[![VS Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-zod-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-zod-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-zod-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-zod-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets&ssr=false#review-details)
[![GitHub Stars](https://img.shields.io/github/stars/ManuelGil/vscode-zod-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-zod-snippets)
[![License](https://img.shields.io/github/license/ManuelGil/vscode-zod-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-zod-snippets/blob/main/LICENSE)

> Snippets to speed up Zod schema creation in your VS Code editor.

## Requirements

- Visual Studio Code 1.46.0 or later (compatible with VSCodium, WindSurf, Cursor, etc.)

## Installation

1. Open **Visual Studio Code**.
2. Go to **Extensions** (`Ctrl+Shift+X` on Windows/Linux or `⌘+Shift+X` on macOS).
3. Search for **Zod Snippets** or install directly from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets).
4. Reload to activate the extension.

## Usage

Type the snippet prefix, then press `Tab` or `Enter` to expand. Here are some key shortcuts:

| Snippet                   | Expansion                           |
| ------------------------- | ----------------------------------- |
| `zod_array_nonempty`      | `z.array(z.string()).nonempty()`    |
| `zod_bigint_positive`     | `z.bigint().positive()`             |
| `zod_date_max`            | `z.date().max(new Date())`          |
| `zod_deep_partial`        | `.deepPartial()`                    |
| `zod_enum`                | `z.enum(...)`                       |
| `zod_schema_keyof`        | `.keyof()`                          |
| `zod_string_nullable`     | `z.nullable(z.string())`            |
| `zod_number_int_positive` | `z.number().int().positive()`       |
| `zod_string_optional`     | `z.optional(z.string())`            |
| `zod_schema_partial`      | `.partial()`                        |
| `zod_schema_passthrough`  | `.passthrough().parse()`            |
| `zod_schema_strip`        | `.strip().parse()`                  |
| `zod_schema_strict`       | `.strict().parse()`                 |
| `zod_promise`             | `z.promise(z.string())`             |
| `zod_function_parameters` | `.parameters()`                     |
| `zod_function_returnType` | `.returnType()`                     |
| `zod_string_max`          | `z.string().max(...)`               |
| `zod_string_min`          | `z.string().min(...)`               |
| `zod_string_length`       | `z.string().length(...)`            |
| `zod_string_email`        | `z.string().email()`                |
| `zod_string_url`          | `z.string().url().nullish()`        |
| `zod_string_emoji`        | `z.string().emoji()`                |
| `zod_string_uuid`         | `z.string().uuid()`                 |
| `zod_string_cuid`         | `z.string().cuid()`                 |
| `zod_string_cuid2`        | `z.string().cuid2()`                |
| `zod_string_ulid`         | `z.string().ulid()`                 |
| `zod_string_regex`        | `z.string().regex(...)`             |
| `zod_string_includes`     | `z.string().includes(...)`          |
| `zod_string_startsWith`   | `z.string().startsWith(...)`        |
| `zod_string_endsWith`     | `z.string().endsWith(...)`          |
| `zod_string_datetime`     | `z.string().datetime()`             |
| `zod_string_ip`           | `z.string().ip({ version: '...' })` |
| `zod_string_trim`         | `z.string().trim()`                 |
| `zod_string_toLowerCase`  | `z.string().toLowerCase()`          |
| `zod_string_toUpperCase`  | `z.string().toUpperCase()`          |

## Contributing

Contributions to the Data Zod Snippets are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-zod-snippets).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-zod-snippets/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-zod-snippets/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-zod-snippets/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-zod-snippets/blob/main/LICENSE) file for full details.
