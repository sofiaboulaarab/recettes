<!-- sites -->
- index.md
  - layout: page
  - contenu: Lorem ipsum

<!-- layouts dans sites -->
- page.html
  - layout: default
  - contenu: <menu> + title + {{content}}

<!-- layouts dans thème (maquillage) -->
- page.html
  - layout: default
  - contenu: title + {{content}}
- default.html
  - contenu: <html><head><meta><style><title></head><body>{{content}}</body></html>
---