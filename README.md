# LunAidigital · Portfolio de Alejandra Noemí Luna

Portfolio one-page responsive de Alejandra Noemí Luna, especialista en educación digital, inteligencia artificial y marketing. La página utiliza las fotografías y el logo suministrados en `assets/` y no depende de imágenes externas. El CV PDF no se publica ni se ofrece para descarga.

## Ejecutar localmente

Desde esta carpeta:

```bash
python3 -m http.server 3000
```

Luego abrir `http://localhost:3000`.

## Publicar

- **GitHub Pages:** subir el contenido de la carpeta al repositorio y publicar desde la rama elegida. `index.html` está en la raíz.
- **Vercel / Netlify:** usar la raíz como directorio del proyecto. Si se configura un build, ejecutar `mkdir -p dist && cp index.html styles.css script.js manus-routes.json dist/ && cp -R assets dist/` y publicar `dist`.

## Personalización

El enlace de LinkedIn está configurado como `lunaidigital` y el botón flotante de WhatsApp utiliza el número `5491164771313`. También se pueden cambiar las fotografías dentro de `assets/` conservando sus nombres.
