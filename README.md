# 🌐 MrSom3body's Homepage

Welcome to the repository for my personal homepage! This site is powered by [Hugo](https://gohugo.io) and styled with the sleek [Blowfish](https://blowfish.page) theme. It's built and deployed using GitHub Actions, ensuring smooth integration and continuous deployment.

## 🛠️ Development & Setup

### 🚀 Getting Started

1. **Clone the repository**  
   First, clone the repository to your local machine:

   ```sh
   $ git clone git@github.com:MrSom3body/MrSom3body.github.io.git
   ```

2. **Activate the Nix environment**  
   If you're using [Nix](https://nixos.org), all dependencies (such as Hugo) are automatically managed, ensuring consistency across different environments:

   ```sh
   $ nix develop
   ```

   > **Note**: You can manually install [Hugo](https://gohugo.io), but using Nix is recommended for a more streamlined setup.

3. **Run the local development server**  
   Launch a local development server to preview the site in real time:

   ```sh
   $ hugo server
   ```

   Your site will be live at `http://localhost:1313`, and changes made to the files will automatically reload in the browser.

### 📂 Project Structure

Here's a quick overview of the directory structure:

- `archetypes/` – Templates for content types
- `assets/` – Source files (SCSS, JS, etc.) that need processing
- `config/` – Hugo configuration files
- `content/` – Markdown files for site content
- `static/` – Files (images, fonts, etc.) served as-is
- `themes/blowfish/` – The theme styling the site

## 🤝 Contributing

Contributions are welcome! If you have suggestions, improvements, or spot a bug, feel free to open an issue or submit a pull request.
