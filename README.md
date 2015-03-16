# Administrator README

This copy of the NHAIS documentation is hosted on GitHub Pages, and built in Jekyll.

## Authoring

### Run a local development copy

`bundle exec jekyll serve`

### Redirecting URLs

Redirect from /foo to /some-url-or-other by including the following in the header of the some-url-or-other page:

```markdown
---
redirect_from: "/foo/"
---
```

**NB**: the trailing slash on the redirect_from URL is significant

## Site administration

### Link checking

To check links, run `bundle exec check-links`
