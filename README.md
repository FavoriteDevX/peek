# 👀 peek.js

> Elegant, zero-dependency, contextual floating micro-previews for links.

`peek` monitors your anchor ecosystem and serves lightweight interactive popover media structures instantly when hovering, mimicking advanced enterprise engine mechanics in under 60 lines of code.

## Usage

Include the target script attributes in your document tree markup:

```html
<a href="/profile" data-peek-src="https://unsplash.com">Hover here to sneak peek profile asset</a>

<script type="module">
  import Peek from './peek.js';
  new Peek({ delay: 200 });
</script>
```
