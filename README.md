# Clean-Blog-Mezzanine
[Start Bootstrap](http://startbootstrap.com/) - [Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/) based theme for [Mezzanine CMS](http://mezzanine.jupo.org/)

## Getting started
To use this as a theme for your Mezzanine-based site:
```shell
$ cd <your-project-dir>
$ git clone https://github.com/vskh/clean_blog_mezzanine.git
$ cat settings.py | sed 's/INSTALLED_APPS\s*=\s*(/INSTALLED_APPS = (\n"clean_blog_mezzanine",/' > settings.py.patched && mv settings.py.patched settings.py
```
