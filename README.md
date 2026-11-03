
# ugurelveren.com

This repository hosts the source code for **ugurelveren.com**, a personal website featuring an interactive terminal-style interface.

## Features
- **Command-line UI:** Explore the site using terminal commands.
- **ASCII Art Welcome:** Custom greeting banner on load.
- **Command-Based Navigation:** Access social profiles, blog, and more.
  
## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/ugurelveren/ugurelveren.github.io.git
   cd ugurelveren.github.io
   ```
2. Open `index.html` in your browser.

## Available Commands
- `about` – Info about Ugur Elveren  
- `blog` – Opens Ugur’s blog  
- `linkedin`, `mastodon`, `github` – Redirects to social profiles  
- `photos` – Opens photo gallery  
- `help` – Lists all commands  

## Dependencies
- **jQuery**  
- **jQuery Terminal Plugin**  

## Customization
- **CSS:** Modify terminal colors in `<style>`  
- **Commands:** Edit the `$('body').terminal()` section  
- **ASCII Art:** Update `<template id="asciiart">`  

## License
MIT License. See [LICENSE](LICENSE).

## Contact
For inquiries, visit [LinkedIn](https://www.linkedin.com/in/ugur-elveren/). 

Enjoy navigating through the interactive terminal! 🎉
