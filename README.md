# TypeScript Primera Parte
Este proyecto fue realizado en el lenguaje de TypeScript, el modelo conciste en una aplicacion llamada UNQify, la cual es muy similar a Spotify.
En UNQfy existe una gran cantidad de temas musicales (tracks)  los cuales siempre pertenecen a un álbum. Un álbum tiene un sólo artista como autor pero un artista puede ser autor de múltiples albumes. Cada track tiene asociado uno o más géneros, que son strings. También existen playlists, que son conjuntos de tracks que pueden pertenecer a diferentes álbumes.
# Api-Rest
Tambien se cuenta con una api, con la cual se puede pedir un album, un artista o una cancion, tambien es capaz de agregar un nuevo album, borrarlo y/o actualizarlo

# Segunda Parte Docker
<img src = "https://1000marcas.net/wp-content/uploads/2020/02/Docker-Logo.png" width = 500 height = 500>
En esta se cuenta con dos servicios, los cuales son Monitor y Notificacion. La tarea del Monitor es monitorear UNQify y comunicar si sufrio algun cambio y avisar a los interesados(algo asi como el patron observer).
El Notificador notifica a los usuarios registrados en un UNQify si un artista agrego una nueva Cancion a su album.
Estos Servicios se ejecutan simultáneamente a traves de una imagen levantada de Docker 
