# DarkFinance

**DarkFinance** is a lightweight browser extension designed to bring a custom dark mode to the RUZ (Расписание Учебных Занятий) website. If you're tired of bright screens while checking your class schedule, this extension provides a sleek and eye-friendly solution.

## Features

- Custom dark theme for the [RUZ website](https://ruz.fa.ru/ruz/main).
- Modifies the background, buttons, tables, inputs, modals, and more to ensure a consistent dark mode experience.
- Custom scrollbar that complements the dark theme.
- Easy to install and doesn't impact browser performance.

## Installation

### For Chrome:
1. Download or clone this repository to your local machine:
   ```bash
   git clone https://github.com/Drewnja/DarkFinance.git

2. Open Chrome and navigate to chrome://extensions/.

3. Enable Developer mode by toggling the switch in the top-right corner.
   
4. Click on Load unpacked and select the directory where you downloaded or cloned the repository.

Development
If you'd like to customize the theme or contribute to the project, follow these steps:

Modify the darktheme.css file with your custom styles.
Reload the extension in Chrome by navigating to chrome://extensions/ and clicking the refresh button next to DarkFinance.
Test your changes by visiting the RUZ website.
Manifest Overview
The extension uses Manifest V3 to define how it operates. Here's a summary of the key parts of the manifest.json:

Name: DarkFinance
Version: 0.0.1
Permissions: The extension requires permission to modify the active tab where the RUZ site is loaded.
Content Scripts: The dark theme (darktheme.css) is applied to the RUZ website (https://ruz.fa.ru/*) via content scripts.
Contributing
Contributions are welcome! Feel free to:

Open issues for any bugs or feature requests.
Submit pull requests with new features, fixes, or improvements.
License
This project is licensed under the MIT License. See the LICENSE file for more details.
