#Como definido, bora começar a arrumar um pouco as coisas...

##Primeiro crie uma virtual env de acordo com esse guia

- https://docs.python-guide.org/dev/virtualenvs/

##Instale essas libs com o pip3

- requests: `pip3 install requests`
- beautifulsoup4 `pip3 install beautifulsoup4`

##Vou pedir para que vc estude sobre:

- [usando Sopa Bonita](https://imasters.com.br/back-end/aprendendo-sobre-web-scraping-em-python-utilizando-beautifulsoup)
- [requests](https://requests.readthedocs.io/pt_BR/latest/user/quickstart.html)
- [O que caralhos são códigos de resposta 1xx, 2xx, 3xx, 4xx, 5xx ...tipo 404](https://www.restapitutorial.com/httpstatuscodes.html)

##Escolha o site que vc irá navegar para coletar dados (pelo amor de HalfPint, sites simples, sem ~muito~ javascript)

- [sugestão de site legal](https://www2.unesp.br/)

##Tarefa final:
- Tente criar um arquivo *.py de uma classe com o nome de "DadosColetados" e outra classe em outro arquivo *.py com o nome "Scrapper".
- Scrapper ficará encarregado de fazer a request, pegar o código html e mandar puro para DadosColetados que por sua vez deve fazer o parsing.
- Após o parsing, armazene em um arquivo *.txt em uma lista de info que vc quiser (pode ser últimas notícias, data de x informação, etc.).

##Material de Apoio:
- [Criar classes](http://pythonclub.com.br/introducao-classes-metodos-python-basico.html)
- [python IO "input output"](https://docs.python.org/3/library/io.html)
- [Herança python](https://algoritmosempython.com.br/cursos/programacao-python/heranca/)