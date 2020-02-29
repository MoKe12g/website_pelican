# chaos.jetzt automated website generator with Pelican
## use
### Setup
```
pip install -r requirements.txt
```

### Generate html
```
make html
```

To check the website:
```
make serve
```
then visit http://localhost:8000/

### Publish

Automated publishing possible, check Pelican documentation


[Documentation Pelican](https://docs.getpelican.com/en/stable/index.html)
[Theme used](https://github.com/alexandrevicenzi/Flex) (little changes)


## write more content

- blogposts in folder 'articles', will automatically appear as newest blogpost
- general pages in folder 'pages', will automatically appear as link in sidebar

## to do
- more articles
- add tags to articles
- create paeges
  - about
  - faq
- switch language to German (needs an [additional plugin](https://github.com/getpelican/pelican-plugins/))
