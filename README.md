# Docker Wordpress Multisite 
Docker-compose configurado para levantar múltiples sitios web en un mismo servidor. 

## Instalación

Instalar docker y docker-compose, luego ejecutar:

```bash
docker-compose up -d
```
Asegurarse de que las carpetas que están montadas como volúmenes tengan el grupo y usuario correcto (que el usuario que está ejecutando el docker tenga permisos de escritura en esas carpetas), de otra manera el servicio mysql arrojará errores de permisos. 

## Uso
Está configurado para dos sitios, uno corriendo en el puerto 81, y el otro en el 83. Por lo que para visualizar de manera local los sitios deben acceder a:

- localhost:81
- localhost:83

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
