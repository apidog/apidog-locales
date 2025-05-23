# Apidog Language Packs

This repository contains localized resource files for Apidog. Each language directory contains the localized string resources for a particular language.

## 🌍 Translation Progress

| Language                    | ISO Code | Client Progress | Server Progress | Overall Status |
| --------------------------- | -------- | --------------- | --------------- | -------------- |
| **English (United States)** | en-US    | 100% ✅         | 100% ✅         | Complete       |
| **Japanese**                | ja-JP    | 100% ✅         | 100% ✅         | Complete       |
| **Portuguese**              | pt-PT    | 100% ✅         | 100% ✅         | Complete       |
| **Spanish**                 | es-ES    | 99% ⏳          | 99% ⏳          | In progress    |

> **Note**: Your translation work will be visible in the product once the overall progress reaches 80%.

## 📁 Repository Structure

```
apidog-locales/
├── app-client/          # Client-side UI translations
│   ├── en-US.json      # English (base language)
│   └── ja-JP.json      # Japanese translations
├── app-server/          # Server-side message translations
│   ├── en-US.json      # English (base language)
│   └── ja-JP.json      # Japanese translations
└── NounReferenceTable.md # Translation terminology glossary
```

## 🚀 Quick Start for Translators

### 1. Choose Your Language

Check the translation progress table above to see available languages or start a new one.

### 2. Review the Glossary

Before starting, familiarize yourself with our [terminology glossary](NounReferenceTable.md) to ensure consistency.

### 3. Set Up Your Branch

Create a branch following our naming convention:

```bash
git checkout -b i18n/{language-code}
# Example: git checkout -b i18n/fr-FR
```

### 4. Start Translating

- **Client UI**: Edit files in `app-client/`
- **Server Messages**: Edit files in `app-server/`
- Use the English files as your reference

### 5. Submit Your Work

Follow our [PR guidelines](#-pull-request-guidelines) when ready to submit.

## 📋 Translation Guidelines

### Branch Naming Convention

```
i18n/{language-code}
```

- Use ISO language codes (e.g., `ja-JP`, `es-ES`, `fr-FR`)
- One branch per language
- Do not mix multiple languages in one branch

### Commit Message Format

```
<type>(<language>): <subject>
```

**Types:**

- `ui`: Client-side UI translations
- `server`: Server-side message translations
- `doc`: Documentation translations
- `fix`: Translation corrections
- `update`: Translation updates

**Examples:**

```bash
ui(ja-JP): translate settings page components
server(es-ES): add error message translations
fix(fr-FR): correct terminology in navigation menu
```

### File Organization

- **Client translations** (`app-client/`): UI elements, buttons, labels, tooltips
- **Server translations** (`app-server/`): Error messages, notifications, system messages

## 🔄 Pull Request Guidelines

### PR Title Format

```
[Language] Translation type - Brief description
```

**Examples:**

- `[ja-JP] UI Translation - Settings and preferences pages`
- `[es-ES] Server Messages - Error handling translations`
- `[fr-FR] Translation Fix - Correct terminology inconsistencies`

### PR Requirements

- [ ] Follow branch naming convention (`i18n/{language}`)
- [ ] Use proper commit message format
- [ ] Reference [terminology glossary](NounReferenceTable.md)
- [ ] List all translated/modified files
- [ ] Update progress table in README (if applicable)
- [ ] Test translations in context when possible

### Review Process

- **Review time**: Within 3 business days
- **Expedited review**: Email support@apidog.com with your PR link
- **Feedback**: We'll provide constructive feedback for improvements
- **Merge criteria**: Consistency, accuracy, and adherence to guidelines

## 🐛 Reporting Translation Issues

Found a translation error or inconsistency? We appreciate your feedback!

### Quick Report

[Create a new issue](https://github.com/apidog/apidog-locales/issues/new?template=translation_issue.md) using our translation issue template.

### Before Reporting

- [ ] Check existing issues to avoid duplicates
- [ ] Verify against the [terminology glossary](NounReferenceTable.md)
- [ ] Provide specific location and context

## 🎯 Translation Best Practices

### Consistency

- Always check the [NounReferenceTable.md](NounReferenceTable.md) for standard terminology
- Maintain consistent tone and style throughout
- Use the same translations for recurring terms

### Context Awareness

- Consider the UI context when translating
- Ensure translations fit within UI constraints
- Test longer translations for layout issues

### Cultural Adaptation

- Adapt content to local cultural norms when appropriate
- Consider local date/time formats and conventions
- Use culturally appropriate examples and references

## 🤝 Contributing

We welcome contributions from the community! Whether you're:

- **Native speakers** helping with accuracy
- **Developers** improving tooling and processes
- **Designers** ensuring translations work well in UI
- **Community members** reporting issues and providing feedback

Your contributions help make Apidog accessible to users worldwide.

### Recognition

- Contributors will be acknowledged in release notes
- Significant contributors may be invited to join our translation team
- Community translators receive early access to new features

## 📞 Support

- **General questions**: Create a [GitHub issue](https://github.com/apidog/apidog-locales/issues/new)
- **Translation support**: Email support@apidog.com
- **Urgent issues**: Email with "Translation Urgent" in the subject line

## 📄 License

This project is licensed under the [MIT License](LICENSE.md).

---

**Thank you for helping make Apidog accessible to users around the world! 🌟**
