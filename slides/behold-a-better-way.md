###  Behold: A Better Way

```apache
<IfModule mod_rewrite.c>
  RewriteEngine on

  # Attempt to load files from production if
  # they're not in our local version
  RewriteCond %{REQUEST_FILENAME} !-d
  RewriteCond %{REQUEST_FILENAME} !-f
  RewriteRule wp-content/uploads/(.*) \
    http://{PROD}/wp-content/uploads/$1 [NC,L]
</IfModule>
```