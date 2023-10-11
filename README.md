# Apidog Language Packs

This repository contains localized resource files for Apidog. Each language directory contains the localized string resources for a particular language.

There are currently 2 "Core" languages for Apidog.

|Language|ISO Language Code|Translation Progress|
|-|-|-|  
|**English (United States)**|en-US| 100% |
|**Japanese**|ja-JP| 100% |
|**Portuguese**|pt-BR|0%|

## Contributing

If you want to give feedback or report an issue with a translation, please create a [new GitHub issue](https://github.com/apidog/apidog-locales/issues/new).

- Please check if a topic about your issue already exists!

## Translation PR Submission Guidelines

### Branch Format

Translations should be submitted to the `i18n/{language}` branch.

```
{language} should be replaced with the target language code, e.g. pt-BR
```

Use one branch per language, do not mix multiple languages in one branch.

### Commit Message Format

The commit message should contain type, language and subject:

```
<type>(<language>): <subject>
```

- type: translation type, e.g. doc, tutorial, ui, etc.
- language: target language code, e.g. pt-BR
- subject: brief description of translation

Example:

```
API Doc(pt-BR): translate API Mocking

ui(fr-FR): translate settings page UI
```

Use `fix` type for translation corrections:

```
fix(pt-BR): fix terminology error
```

Clear and simple commit messages can help track translation progress.

Adjust the format as needed for your project.

### PR Title Format

- PR title should clearly state the translated language and content (e.g. "Translate Portuguese Tutorial")

- PR description should list all translated files.

- Follow the terminology glossary to ensure consistency.

- Note any translation corrections in PR description.

Update language list after adding a new translated language.

### Note to Translators

Thank you for your translation contribution! 

We will review the PR within 3 working days after receiving it. When the translation progress is up to 80%, your work will be visible in the product soon.

## License
[MIT](LICENSE.md)