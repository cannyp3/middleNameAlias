# Middle Name Alias

Middle Name Alias is a lightweight single-file web app that turns a memorable site or service label into a name-like alias using a reversible letter-shift algorithm. It is designed for personal tagging, recall, and light obfuscation rather than real security or cryptographic protection. [file:1]

## What it does

The app encodes text with a reversible Vigenere-style cipher that operates on letters only, then reshapes the output into title case so the result looks more like a plausible name than random text. The same secret phrase can later be used to decode the alias back to the original label. [file:1]

Typical use cases include creating memorable stand-ins for account labels, personal reference systems, or private naming conventions where readability matters more than strong secrecy. The built-in description explicitly warns that the app is not intended for serious privacy or cryptography. [file:1]

## Features

- Single HTML file with no build step or backend dependency, making it easy to open locally in any modern browser. [file:1]
- Reversible encode and decode workflow based on a secret phrase. [file:1]
- Name-styled output formatting for better readability and recall. [file:1]
- Letter-only transformation behavior, which keeps the core algorithm simple and predictable. [file:1]
- Clear positioning for personal organization rather than secure data protection. [file:1]

## How to use

1. Open `middle-name-alias.html` in a browser. [file:1]
2. Enter the original label you want to disguise, such as a website or service name. [file:1]
3. Provide a secret phrase that acts as the reversible key. [file:1]
4. Generate the alias and save it as your readable stand-in. [file:1]
5. When needed, enter the alias with the same secret phrase to recover the original label. [file:1]

For example, the app notes that a label such as `ExampleShop` can be converted into a name-like alias such as `Marolen`, then decoded later with the same phrase. [file:1]

## Security note

This project should be treated as an obfuscation utility, not a password manager, encryption tool, or security product. Because the transformation is intentionally simple and optimized for memorability, it should not be relied on to protect sensitive credentials, regulated data, or confidential identifiers. [file:1]

## Project structure

The application is packaged as a single self-contained HTML file, which likely includes the UI, styling, and browser-side logic together. That makes it easy to share, inspect, and modify without additional tooling. [file:1]

## Good fit

This app is a good fit for personal workflows where someone wants aliases that are easier to remember than random strings, especially for labels that do not require strong protection. It is less appropriate anywhere formal security, enterprise authentication, or irreversible anonymization is required. [file:1]
