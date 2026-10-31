# Proyecto Angular: MiMascota (Clínica Veterinaria)
**Cuarta Práctica Calificada**

## Estructura de Componentes y Páginas
- **Componente Cabecera (`src/app/components/cabecera`)**: Fondo negro (`#000000`) con letras blancas y menú de navegación hacia `Nosotros` y `Servicios`.
- **Componente Pie de Página (`src/app/components/pie-pagina`)**: Fondo negro (`#000000`) con letras blancas y lista vertical de opciones con los enlaces solicitados:
  - Perros: https://tienda.mascotas365.com/perros
  - Peluquería: https://mascotas365.com/establecimiento/buuf-boutique-estetica-canina/
- **Página Nosotros (`src/app/pages/nosotros`)**: Contiene un carrusel de 3 imágenes de la veterinaria e información institucional.
- **Página Servicios (`src/app/pages/servicios`)**: Plantilla base de Bootstrap que muestra los tres servicios ofrecidos por la veterinaria: **Emergencias médicas**, **Hospedaje** y **Adiestramiento**.

## Cómo ejecutar en Visual Studio Code (VSC)
1. Abre la carpeta `MiMascota` en Visual Studio Code.
2. Abre la terminal integrada (`Ctrl + Ñ` o `Ctrl + ~`) y ejecuta:
   ```bash
   npm install
   ng serve -o
   ```
3. Se abrirá automáticamente en `http://localhost:4200`.

## Cómo publicarlo en GitHub y GitHub Pages
```bash
git init
git add .
git commit -m "Cuarta Practica Calificada - Proyecto Angular MiMascota"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/MiMascota.git
git push -u origin main

# Para publicar la web en GitHub Pages:
ng build --base-href "https://TU_USUARIO.github.io/MiMascota/"
npx angular-cli-ghpages --dir=dist/mi-mascota/browser
```
