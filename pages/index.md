---
menu: !file menu.md
news: !file news.yaml
---
{{{menu}}}

# Hírek

{{#news}}
<article>

## {{title}}

{{content}}

{{date}}
</article>
{{/news}}