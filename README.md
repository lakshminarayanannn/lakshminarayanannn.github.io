# Lakshminarayanan Portfolio (Jekyll)

Static Jekyll rebuild of the Lakshminarayanan portfolio inspired by the React design.

## Structure
- `_data/site.yml`: Site-wide metadata (name, tagline, contact, social links).
- `_posts/`: Long-form blogs (`layout: post`).
- `_microblog/`: Short-form thoughts.
- `_photos/`: Photo entries with gradients.
- `_work/`: Work history entries consumed by pages.
- `_layouts/`: `default`, `post`, and `photo` layouts.
- `_includes/`: Shared navigation and footer.
- `assets/css/main.css`: Single stylesheet mirroring the JSX styling.
- `index.html`, `blogs.html`, `microblog.html`, `work.html`, `photos.html`: Public pages.

## Running Locally
```
jekyll serve
```
Install Jekyll if it is not available in your environment. GitHub Pages will build the site automatically.
