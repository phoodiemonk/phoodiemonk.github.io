# Phoodiemonk

Welcome to the Phoodiemonk repository! This project serves as the static landing and recipe site for the **Phoodiemonk** homechef brand, proudly hosted via GitHub Pages at [phoodiemonk.github.io](https://phoodiemonk.github.io/).

## Project Setup & Features
Throughout our build session, the following tasks and configuration steps were completed:

### 1. Development Environment Setup
- **GitHub CLI Installation:** We securely downloaded and installed the GitHub CLI (`gh`) to `~/.local/bin` and added it directly to the system `PATH` via `~/.zshrc`.
- **Git Dependencies:** Triggered an automatic installation of Xcode Command Line Tools to ensure `git` was available on the Mac.
- **CLI Authentication:** Successfully bootstrapped an interactive `gh auth login` flow, sending an OAuth device code to pair the terminal directly to the user's GitHub account.
- **Repository Setup:** Initially scaffolded a local `Phoodiemonk` repository and pushed it. Because the desired website URL was the root domain (`https://phoodiemonk.github.io/`), we later detached from that repo, linked the origin to the `phoodiemonk.github.io` repository, force-pushed the `main` branch, and forcefully enabled GitHub Pages via the API.

### 2. Website Design & Build
- **Tech Stack:** Built natively using raw HTML5 and an elegant, custom CSS3 architecture avoiding bloated frameworks.
- **Premium Aesthetics:** Integrated modern frosted-glass effects (glassmorphism), refined Google Fonts (`Playfair Display` for serif headers, `Outfit` for sans-serif body), and smooth dynamic CSS animations.
- **Asset Generation:** Used generative AI tools to create completely custom, high-quality 4K imagery for the layout:
  - A friendly, professional homechef portrait.
  - A mouth-watering Truffle Pasta dish image.
  - A vibrant Gourmet Avocado Toast image.
- **Site Structure:** 
  - `index.html`: Home page featuring a split hero layout.
  - `pasta.html`: Individual recipe page for Truffle Pasta.
  - `avocado.html`: Individual recipe page for Avocado Toast.
  - `style.css`: All premium design tokens and cascading styles.
- **Interactive Navigation:** Built a sticky header with a smooth, hover-activated dropdown mapping to the newly created recipe pages.

### 3. Branding & Custom Logo Integration
- **Logo Integration:** Sourced the true "Phoodiemonk Rustic Indian Curries" mortar and pestle brand logo by downloading it securely from a Google Drive URL.
- **Visual Scheme Extraction:** Evaluated the graphic's layout and colors, extrapolating its deep, rustic maroon/chestnut red. We then completely replaced the site's default orange design tokens with this exact maroon hue—syncing buttons, gradients, dropping shadows, and hover elements to match.
- **Image Optimization:** Replaced the text-based title placeholder in the main `<nav>` with the downloaded graphic logo. Adjusted the image size explicitly to `height: 70px` while pinning `object-fit: contain` to preserve its natural aspect ratio perfectly.

### Deployment
Any code changes pushed to the `main` branch of this repository are automatically propagated and published to the live GitHub Pages site.
