# Zod Snippets for VSCode Editor

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-zod-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-zod-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-zod-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-zod-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-zod-snippets&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-zod-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-zod-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-zod-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-zod-snippets/blob/main/LICENSE)

This extension for Visual Studio Code adds snippets for Zod.

## Requirements

- VSCode 1.46.0 or later

## Usage

### Snippets

Type part of snippet, press `Tab` or `Enter`, and the snippet unfolds. Below is a list of the most important shortcuts.

| Snippet | Purpose |
| --- | --- |
| zod_array_nonempty | z.array(z.string()).nonempty() |
| zod_bigint_positive | z.bigint().positive() |
| zod_date_max | z.date().max(new Date()) |
| zod_deep_partial | const ... = ....deepPartial(); |
| zod_enum | z.enum(...) |
| zod_schema_keyof | const ... = ....keyof(); |
| zod_string_nullable | z.nullable(z.string()) |
| zod_number_int_positive | z.number().int().positive() |
| zod_string_optional | z.optional(z.string()) |
| zod_schema_partial | const ... = ....partial(); |
| zod_schema_passthrough | ....passthrough().parse() |
| zod_schema_strip | ....strip().parse() |
| zod_schema_strict | ....strict().parse() |
| zod_promise | z.promise(z.string()) |
| zod_function_parameters | ....parameters() |
| zod_function_returnType | ....returnType() |
| zod_string_max | z.string().max(...) |
| zod_string_min | z.string().min(...) |
| zod_string_length | z.string().length(...) |
| zod_string_email | z.string().email() |
| zod_string_url | z.string().url().nullish() |
| zod_string_emoji | z.string().emoji() |
| zod_string_uuid | z.string().uuid() |
| zod_string_cuid | z.string().cuid() |
| zod_string_cuid2 | z.string().cuid2() |
| zod_string_ulid | z.string().ulid() |
| zod_string_regex | z.string().regex(...) |
| zod_string_includes | z.string().includes(...) |
| zod_string_startsWith | z.string().startsWith(...) |
| zod_string_endsWith | z.string().endsWith(...) |
| zod_string_datetime | z.string().datetime() |
| zod_string_ip | z.string().ip({ version: '...' }) |
| zod_string_trim | z.string().trim() |
| zod_string_toLowerCase | z.string().toLowerCase() |
| zod_string_toUpperCase | z.string().toUpperCase() |

## Connect with me

[![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge&logo=github)](https://github.com/ManuelGil)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- [NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)
- [NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
- [Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)
- [T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)
- [CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)
- [CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
- [CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)
- [Moodle Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-moodle-snippets)
- [Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)

## Authors

- **Manuel Gil** - _Owner_ - [ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/vscode-zod-snippets/contributors) who participated in this project.

## License

Zod Snippets for VSCode is licensed under the MIT License - see the [MIT License](https://opensource.org/licenses/MIT) for details.
