Iza Vene | Personal Brand & Minimalist Blog

This repository contains the source code for my personal brand website. The design is a single-page layout that integrates a professional portfolio with a minimalist blog section, reflecting my work and my passion for philosophy. 
🛠️ Built With

    Static Site Generator: Jekyll

    Hosting: GitHub Pages (Automatic builds on push)

    Styling: Custom CSS with an earthy, minimalist aesthetic

🏗️ How to Manage Content

This site is designed to be low-maintenance. Because it uses Jekyll, the "About Me" and "Blog" sections are updated through simple file changes. 
Adding a Blog Post

To add a new post to the bottom of the page:

    Navigate to the _posts/ directory.

    Create a new file named YYYY-MM-DD-your-title.md.

    Add the front matter at the top:
    Markdown

    ---
    layout: post
    title: "Your Post Title"
    ---
    Your short description or philosophy excerpt goes here.

    Commit and push to the main branch. GitHub Pages will rebuild the site automatically. 

Editing the "About Me" Section

    The text for your bio and professional work is located directly in index.html.

    Simply update the text within the <section id="about"> tags to refresh your profile.

📁 Repository Structure

    _posts/: All blog entries (Markdown).

    _layouts/: The default.html wrapper that includes the sidebar.

    assets/css/: Custom styles mirroring the orange and beige brand colors.

    index.html: The single-page core containing the About and Blog loop.

    _config.yml: Global settings for the site.
