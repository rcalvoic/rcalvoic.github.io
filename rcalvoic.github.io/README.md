# rcalvoic.github.io

This repository is for the personal website of Professor Rafael A. Calvo, hosted using GitHub Pages and built with Jekyll.

## Project Structure

- **_config.yml**: Configuration file for the Jekyll site, containing site-wide settings such as title and description.
- **_layouts/default.html**: Default layout for the site, defining the HTML structure and linking stylesheets and scripts.
- **_includes/**: Directory for reusable snippets of code or HTML that can be included in other templates or layouts.
- **_posts/**: Directory for blog posts, where each post is written in Markdown and follows the naming convention (YYYY-MM-DD-title.md).
- **index.md**: Homepage of the Jekyll site, customizable to display various elements and content.
- **style.css**: CSS file for styling the HTML elements and layout of the site.
- **README.md**: Documentation for the project, providing setup and usage instructions.

## Getting Started

To set up and run the Jekyll site locally, follow these steps:

1. **Install Jekyll**: Ensure you have Ruby and Bundler installed. Then, install Jekyll by running:
   ```
   gem install jekyll bundler
   ```

2. **Clone the Repository**: Clone this repository to your local machine:
   ```
   git clone https://github.com/yourusername/rcalvoic.github.io.git
   ```

3. **Navigate to the Project Directory**:
   ```
   cd rcalvoic.github.io
   ```

4. **Install Dependencies**: Run Bundler to install the necessary gems:
   ```
   bundle install
   ```

5. **Run the Jekyll Server**: Start the Jekyll server to preview your site locally:
   ```
   bundle exec jekyll serve
   ```

6. **Access the Site**: Open your web browser and go to `http://localhost:4000` to view your site.

## Deployment

This site is automatically deployed to GitHub Pages. Any changes pushed to the `main` branch will be reflected on the live site.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements for the site.