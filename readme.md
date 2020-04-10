## RUN
```
 docker run -d -it --name my-apache-app -p 8088:80 -v "$PWD/docs":/usr/local/apache2/htdocs/ httpd:2.4
```

## BROWSER
Open your browser to: http://localhost:8088
