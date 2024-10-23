# Reporte Mailchimp

Este repositorio contiene un tablero con métricas de correos enviados a través de Mailchimp. El objetivo es proporcionar un análisis visual y fácil de interpretar sobre el rendimiento de las campañas de correo electrónico.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Instalación

Para utilizar este tablero, asegúrate de tener R y RStudio instalados en tu máquina. Luego, clona este repositorio y ejecuta el siguiente comando para instalar las dependencias necesarias:

```bash
renv::restore()
```
renv permite gestionar las dependencias del proyecto, asegurando que todos los paquetes utilizados son compatibles con la versión de R en uso. Si no tienes renv instalado, puedes hacerlo ejecutando:

```bash
install.packages("renv")
```

## Uso
Para generar el tablero, abre el archivo dashboard.qmd en RStudio y ejecuta el documento. Asegúrate de tener acceso a los datos de Mailchimp que deseas analizar.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE.md para más detalles.

## Enlace
Puedes ver el tablero en línea [aquí](https://metadocencia.github.io/reporte-mailchimp/dashboard.html).
