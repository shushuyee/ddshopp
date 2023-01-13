
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://shushuyee.github.io/ddshopp/index.html$1 [R,L]
