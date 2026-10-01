# Reese's portfolio site

This is a no-build, static portfolio: publish it free with GitHub Pages or Netlify Drop. Its work section is an equal-weight project index - it intentionally has no featured project.

## Before publishing

1. Replace each `https://github.com/` project link in `index.html` with the repository link for that project.
2. Add your real LinkedIn link in the header or footer if you would like it shown.
3. Preview locally by opening `index.html` in a browser.

## Add a project later

In `index.html`, copy a complete `<article class="project-card ...">` from the `all-projects` section and update its title, description, tags, and link. The existing grid will automatically place it alongside the other work.

## Free publishing

### GitHub Pages

Create a repository, upload the contents of this folder, then open **Settings → Pages** and select the `main` branch as the source. GitHub will provide the public address.

### Netlify Drop

Visit [app.netlify.com/drop](https://app.netlify.com/drop) and drag this folder into the page. Netlify immediately gives you a public URL.
