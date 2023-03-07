# micro-frontend

Pequeño proyecto de microfrontends para entender y aprender como se pueden conectar distintos módulos y que puedan funcionar de manera independiente.

Los distintos módulos (container, marketing, auth y dashboard) se pueden trabajar de manera independiente, al subir los cambios de nuestra rama al repositorio, se ejecuta una Action de GitHub que ejecuta los comandos definidos en el workflow del módulo en cuestión.

Estos cambios se suben a **Amazon Web Services**, en concreto a un **S3 Bucket**, donde se muestra una página estática. Con **Cloudfront** se expone este bucket, y según los comandos fijados se invalida la caché de los archivos necesarios para mostrar los nuevos cambios.


Tecnologías utilizadas:
- React
- React Router
- Vue
- Material UI
- AWS (S3 y Cloudfront)
- Webpack
- GitHub Actions
- GitHub Workflows
- CI/CD

*La página no es funcional, la mayor parte es puramente decorativa.*
