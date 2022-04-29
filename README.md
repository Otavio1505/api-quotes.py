# api-quotes.py
Api capaz de captar quotes (citações) de todas as páginas do site: https://quotes.toscrape.com/

# Sobre o projeto
Desenvolvido durante aprendizado de API's

# Como funciona?
Atráves do import da biblioteca scrapy e a declaração da url do site desejado será criado uma def parse que por meio do parâmetro response.xpath será aberto uma varredura por todo o site. Com a criação do laço for, é declarado os dados que serão filtrados, sendo eles: title,author e tags. O programa também é capaz de identificar se há mais páginas para varredura, caso positivo, haverá request em uma nova url, através do rsponse.urljoin. Dicionário .json será aberto após o runspider da api ser digitada no terminal.

![a](https://user-images.githubusercontent.com/84475339/166062149-28ae611d-465f-4018-bf87-7dcac1cee661.png)
