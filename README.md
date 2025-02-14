# Github Styling for Hugo

A Hugo theme forked from [github-style-plus](https://github.com/kurt-liao/github-style-plus), which was originally forked from [github-style](https://github.com/MeiK2333/github-style). This theme includes several unique enhancements and customizations.

[Live Demo](https://blog.nove-b.dev/)

## Key Features & Improvements

1. **Cleaner Post List View**
   - Removed tag listings from the post list page
   - Improves focus on actual content
   - Compare: [Original with tags](https://meik2333.com//post/) vs [Our clean design](https://blog.nove-b.dev/post/)

2. **Smart Content Preview**
   - Automatically uses the first 140 characters as excerpt when no summary is provided
   - More consistent post previews without manual configuration

3. **Enhanced Social Integration**
   - Added Mastodon icon to profile links
   - Expanded social media sharing options

4. **Improved Search Functionality**
   - Enhanced search performance
   - Try it yourself: Compare [github-style](https://meik2333.com//) vs [github-styling](https://blog.nove-b.dev/)

## Quick Start

### 1. Create a New Hugo Site
```bash
hugo new site mysite
cd mysite
```

### 2. Install the Theme
```bash
git submodule add https://github.com/nove-b/github-styling.git themes/github-styling
```

### 3. Update the Theme
If you've just installed the theme, you already have the latest version. To update an existing installation:

```bash
cd themes/github-styling
git pull
```

### 4. Directory Structure Update
Rename your posts directory to match the theme structure:
```bash
cd <your-project-folder>
mv content/posts content/post
```

## In Progress

- [  ] No issues in progress

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


---

For more information and detailed documentation, visit the [demo site](https://blog.nove-b.dev/).