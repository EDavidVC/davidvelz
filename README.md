# davidvelz

Página de presentación personal preparada para publicarse en **GitHub Pages**.

## Estructura

```text
.
├── index.html              # Página principal (oficial)
├── alternativa/
│   └── index.html          # Versión alternativa
├── css/
│   ├── main.css            # Estilos de la página principal
│   └── alternativa.css     # Estilos de la versión alternativa
├── js/
│   ├── main.js             # Scripts de la página principal
│   └── alternativa.js      # Scripts de la versión alternativa
└── README.md
```

## Publicar en GitHub Pages

1. Sube los cambios al repositorio:
   ```bash
   git add .
   git commit -m "Update site"
   git push origin main
   ```
2. En GitHub, entra a **Settings > Pages**.
3. En **Build and deployment**, selecciona:
   - **Source:** Deploy from a branch
   - **Branch:** `gh-pages` (o `main`)
   - **Folder:** `/ (root)`
4. Guarda los cambios.

## URLs esperadas

- Principal: `https://edavidvc.github.io/davidvelz/`
- Alternativa: `https://edavidvc.github.io/davidvelz/alternativa/`
