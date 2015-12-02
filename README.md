# IDEBPB

Este projeto tem como intuito amparar as visualizações do IDEB da Paraíba em mapa, que foi utilizada na apresentação sobre [Exibindo dados com Geolocalização](http://www.slideshare.net/lucachaves/exibindo-dados-com-geologalizao).

Para exibir as visualizações basta ativar algum servidor HTTP, como por exemplo, utilizando algumas destas opções:

```
$ http-server -p 8008 &
$ python -m SimpleHTTPServer 8000 &
```

Os dois mapas disponibilizados foram extraídos de bases de mapas abertas e adaptadas ao HTML usando o [mapstarter](http://mapstarter.com/) através da biblioteca [d3.js](http://d3js.org/).
