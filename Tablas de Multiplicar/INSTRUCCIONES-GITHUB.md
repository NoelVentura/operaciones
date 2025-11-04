# 📝 Instrucciones para Publicar en GitHub Pages

## Paso 1: Crear el Repositorio en GitHub

1. Ve a [GitHub.com](https://github.com) e inicia sesión
2. Haz clic en el botón **"+"** en la esquina superior derecha
3. Selecciona **"New repository"**
4. Completa el formulario:
   - **Repository name**: `tablas-multiplicar-noelito` (o el nombre que prefieras)
   - **Description**: "Aplicación web educativa para aprender operaciones matemáticas"
   - **Visibility**: Selecciona **Public** (para GitHub Pages gratuito)
   - **NO marques** "Initialize this repository with a README"
   - **NO agregues** .gitignore ni licencia
5. Haz clic en **"Create repository"**

## Paso 2: Actualizar el Remoto Local

Después de crear el repositorio, GitHub te mostrará la URL. Ejecuta estos comandos en la terminal:

```bash
# Si el repositorio ya existe, actualiza el remoto:
git remote set-url origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git

# O si necesitas agregar un nuevo remoto:
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
```

## Paso 3: Subir los Archivos

```bash
# Subir todos los cambios
git push -u origin master
```

Si tienes problemas, puedes usar:
```bash
git push -u origin master --force
```
(⚠️ Solo usa --force si estás seguro de que quieres sobrescribir el remoto)

## Paso 4: Configurar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, busca y haz clic en **Pages**
4. En **Source**, selecciona:
   - Branch: **master** (o main)
   - Folder: **/ (root)**
5. Haz clic en **Save**
6. Espera unos minutos y tu sitio estará disponible en:
   `https://TU-USUARIO.github.io/TU-REPOSITORIO/`

## ⚠️ Nota Importante

Asegúrate de que todos los archivos estén en la carpeta raíz del repositorio, incluyendo:
- ✅ index.html
- ✅ pagina-inicio.html
- ✅ tablas-multiplicar.html
- ✅ dividir.html
- ✅ sumar.html
- ✅ restar.html
- ✅ carpeta `public/` con todas las imágenes
- ✅ .nojekyll

¡Listo! Tu aplicación estará en línea 🚀

