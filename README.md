# [Elias Rojas](https://eliasrojas.github.io)

## How to's

### Download changes

This should be done before working on the files

Open console/terminal at project folder.

```bash
git pull
```

This should be done before working and before uploading the files.

### Upload changes

Open console/terminal at project folder.

```bash
git pull
git add .
git commit -m "short message with changes made"
git push
```

### Add apex and ```www``` subdomain

#### Apex

 - Add ```A``` record to @ on dns provider with the following ips:

```
192.30.252.153
192.30.252.154
```

[```ALIAS``` or ```ANAME``` record](https://help.github.com/articles/setting-up-an-apex-domain/#configuring-an-alias-or-aname-record-with-your-dns-provider)

 - Add a file named ```CNAME``` to root of project with the apex to use (e.g. eliasjrojas.com) as it's content.
 - 
#### ```WWW```
Add a cname record pointing to repo's name on dns provider.

# [Start Bootstrap](http://startbootstrap.com/) - [Stylish Portfolio](http://startbootstrap.com/template-overviews/stylish-portfolio/)

[Stylish Portfolio](http://startbootstrap.com/template-overviews/stylish-portfolio/) is a responsive, one page portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). The theme features multiple content sections with an off canvas navigation menu.

## Getting Started

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Start Bootstrap](http://startbootstrap.com/template-overviews/stylish-portfolio/)
* Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio.git`
* Fork the repo

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/stylish-portfolio/).

## Creator

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2016 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio/blob/gh-pages/LICENSE) license.
