Created because the distill v2 template fails to create the byline (containing authors etc.) if the article is placed inside a container.
## CDN Links

You can include Distill.js directly from jsDelivr CDN:

### Regular version
```html
<script src="https://cdn.jsdelivr.net/gh/afspies/distill_js@main/distill.js"></script>
```

### Minified version

```html
<script src="https://cdn.jsdelivr.net/gh/afspies/distill_js@main/distill.min.js"></script>
```

```

Note that using `@main` in the URL points to the main branch. If you create releases with version tags (recommended for production use), you could use those instead, like `@1.0.0`. This would make the URLs more stable and predictable for production environments.

If you plan to create releases, you might want to add version-specific examples as well:

```markdown
Specific version (recommended for production)
```

```html
<script src="https://cdn.jsdelivr.net/gh/afspies/distill_js@1.0.0/distill.min.js"></script>
```
