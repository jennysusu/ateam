RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://jennysusu.github.io/ateam/index.html$1 [R,L]
