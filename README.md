# README---Multilingual - English
How to Make README.md Multilingual

When creating my first GitHub project, I was introduced to the concept of README.md, an important file that illustrates and describes your entire project on GitHub. While working on this document, I wondered how to make it available in different languages, since projects can easily be viewed by users worldwide. In this article, learn how to make your project descriptions multilingual and why this is important for accessibility.

### 1. Creating Separate README Files
The simplest and most straightforward way to support multiple languages is to create separate README.md files for each language. Each file should follow the naming convention README.lang.md, where lang represents the language code (e.g., en for English, pt for Portuguese, es for Spanish). For example:

- README.md (default)
- README.pt-PT.md (Portuguese)
- README.es-ES.md (Spanish)

In the main README (usually in English), you can provide links to translated versions:

# README in Different Languages

(Choose your language below / Escolha o seu idioma abaixo / Elija su idioma abajo)
- [![English](https://img.shields.io/badge/Language-English-blue)](README.md)
- [![Português](https://img.shields.io/badge/Language-Português-green)](README.pt-PT.md)
- [![Español](https://img.shields.io/badge/Language-Español-red)](README.es-ES.md)

2. Multi-Language Sections in a Single README
Another approach is to keep all translations in a single README.md file. You can organize the content into sections, each dedicated to a specific language. This is useful for smaller projects or when translations are not extensive.

# Project Name  

## English  
[English version of the README content]  

## Português  
[Versão em português do conteúdo do README]  

## Español  
[Versión en español del contenido del README]

---
### 3. Using GitHub Actions to Switch Languages
For an advanced solution, you can use GitHub Actions or other automated scripts to detect a visitor's preferred language and display the corresponding README. This requires creating a script that updates the main README.md based on the selected language, though it is a more complex and less common option.

### 4. Internationalization (i18n) with External Tools
There are also i18n tools that help manage and automate translations for documentation files, including README.md. These tools can be integrated into your workflow to simplify maintaining multiple README versions in different languages.

### Conclusion
Supporting multiple languages in your README.md is an investment that can make your project more inclusive and accessible. Choose the approach that best fits your project's size and needs, ensuring users from different regions can interact with it effectively.
