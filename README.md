# static-site-base

This project starts by using jekyll to generate static sites  and deploying them somewhere. 
Later I want to add a solution to add a formular to those sites.

## Init Jekyll
```
docker build -t 'site' .
docker run -ti -v /.../static-site-base/site:/home/jekyll/site --rm site bash

# inside container
jekyll new site
```
