Docker example on using a server like Apache, in particular showing port publishing
`docker run -dit --rm --name my-apache-web -v ${PWD}\myweb:/usr/local/apache2/htdocs/ -p 8080:80 httpd`