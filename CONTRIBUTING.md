# Guía de Contribución

¡Gracias por tu interés en contribuir a este proyecto! 
Apreciamos todo tipo de contribuciones: código, documentación, reportes de errores, ideas y más.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (v18 o superior)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)

## Cómo contribuir

### 1. Haz un fork del repositorio
Crea tu propia copia del proyecto haciendo clic en el botón **Fork** en GitHub.

### 2. Clona tu fork
```bash
git clone https://github.com/tu-usuario/nombre-del-proyecto.git
cd nombre-del-proyecto
```
### 3. Crea una rama para tu cambio
Usa una rama con un nombre descriptivo:
```
git checkout -b fix/bug-en-el-formulario
```
### 4. Realiza tus cambios
Edita el código, corrige errores o mejora la documentación.

### 5. Ejecuta las pruebas
Asegúrate de que todo funcione correctamente antes de enviar tu contribución:
```
npm test
```

### 6. Haz commit de tus cambios
Usa mensajes claros y concisos:
```
git commit -m "Corrige error en el formulario de registro"
```

### 7. Envía tu rama al fork
```
git push origin fix/bug-en-el-formulario
```

### 8. Crea un Pull Request (PR)
Ve a GitHub y abre un Pull Request hacia la rama principal (main o develop) del repositorio original.

## Estilo de código

- Sigue la guía de estilo del proyecto (consulta el archivo .editorconfig o .eslintrc).
- Usa nombres de variables descriptivos.
- Incluye comentarios cuando el código no sea evidente.

## Pruebas
Si agregas una nueva funcionalidad, por favor incluye pruebas automáticas.
Ejemplo:
```
npm run test
```

## Reportar errores
Si encuentras un bug, abre un Issue con esta información:

- Descripción del problema
- Pasos para reproducirlo
- Comportamiento esperado
- Capturas de pantalla o logs (si es relevante)

¡Gracias por ayudar a mejorar este proyecto!
