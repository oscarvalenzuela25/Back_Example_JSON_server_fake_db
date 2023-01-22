# Pasos para levantar JSON Server

### Instalar dependencia global
```
npm install -g json-server
```

### Ahora creamos un archivo db.json, por ejemplo
```
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

### Levantamos nuestro server
```
json-server --watch db.json
```

### Listo
Si vas al endpoint http://localhost:3000/posts/1 deberia de salirte
```
{ "id": 1, "title": "json-server", "author": "typicode" }
```

### Documentación
[Link a Documentación](https://github.com/typicode/json-server)
