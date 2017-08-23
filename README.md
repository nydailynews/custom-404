# Custom 404 and index views on apache

## Implementing the custom index template
Edit the httpd.conf file and in the `<Directory>` entry for your server add these lines:
```
    HeaderName /404/header.html
    ReadmeName footer.html
```
