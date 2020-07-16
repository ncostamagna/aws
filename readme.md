# Indice
- [ELK Stack (Elastic Stack)](#elk---elastic-stack)


<br />

# ELK - Elastic Stack
Se compone por varios comopentes:
- Elastic Search
- Log Stash
- Kibana
https://www.elastic.co/products/
<br />

### Elastic Search
Una base de datos donde solo vamos a poder almacenar cadenas de texto, en este caso estas cadenas de texto van a ser lineas de nuestro log.<br />
Esta optimizado para realizar busquedas rapidas, casi instantaneas sobre difernetes indices donde se van a almacenar estos logs.<br />
Vamos a tener una base de datos donde vamos a poder comunicarnos utilizando HTTP y esto nos va a devolver un fichero JSON<br /><br />

Vamos alevantarlo desde el servicio de **Amazon ElasticSearch Service**

### Log Stash
Podemos cetralizar los Logs y hacer transformaciones de ellos antes de mandarlos a la bd (ElasticSearch), o mandarlo directamente a la base de datos

### Kibana
Interface grafico, mediante el cual vamos a poder ver esos datos de diferentes formas.<br />
Diferentes graficas, el link es https://www.elastic.co/kibana <br/>

### Beats



https://www.youtube.com/watch?v=tcB3Gc5Oycg&t=320s

<br />En 6:24

