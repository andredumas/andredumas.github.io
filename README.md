André Dumas Website
===================

Contains static files and resources for my personal website http://andredumas.id.au/.

```sh
cd andredumas.github.io
docker run -i -v $PWD:/site -p 4000:4000 -t andredumas/github-pages serve --watch
```