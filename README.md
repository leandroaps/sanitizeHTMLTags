# sanitizeHTMLTags
This snippet can be used to remove HTML/XML tags from a string.

```
const sanitizeHTMLTags = str => str.replace(/<[^>]*>/g, '');
```

**Usage:**
```
sanitizeHTMLTags('<p><em>lorem</em> <strong>ipsum</strong></p>'); // 'lorem ipsum'
```
