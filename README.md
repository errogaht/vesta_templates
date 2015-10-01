# vesta_templates

### What is this
This repository contains useful config templates for [Vesta CP](https://vestacp.com)

Work with vesta 0.9.8

### Templates list

* Drupal 7
* Redmine
* Laravel 5.1

### Installation
To install thoose templates just:

```sh
cd /usr/local/vesta/data/templates/web
git clone https://github.com/errogaht/vesta_templates.git
cp -R vesta_templates/apache2 .
cp -R vesta_templates/nginx .
rm -R vesta_templates
```