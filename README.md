# Portal Noreste (GitHub Pages)

Portal cautivo externo para redes de invitados (Aruba Instant On). Diseño consistente con el logo de Noreste y redirección a Facebook tras aceptar términos.

## Estructura

```
portal-noreste/
├─ index.html
├─ .nojekyll
└─ assets/
   └─ logo.png   ← sube aquí el logo (la imagen provista)
```

## Publicación (GitHub Pages)

1. Sube los archivos anteriores a la rama `main`.
2. Ve a Settings → Pages.
3. Source: “Deploy from a branch”.
4. Branch: `main` y carpeta `/root`. Guarda.
5. URL resultante: `https://<tu-usuario>.github.io/portal-noreste/`

## Aruba Instant On (Portal Externo)

- URL de portal: `https://<tu-usuario>.github.io/portal-noreste/`
- Autenticación: Autenticación de Invitado (click-through).
- Dominios permitidos:
  - `<tu-usuario>.github.io`
  - `github.io`
- (Opcional) Permitir Facebook antes de aceptar: añade `facebook.com`, `m.facebook.com`, `fbcdn.net`, `fbsbx.com`, `static.xx.fbcdn.net`.

## Personalización

- Cambiar destino del botón en `index.html` (id `btnGo`).
- O pasar una URL dinámica:  
  `https://<tu-usuario>.github.io/portal-noreste/?to=https://www.facebook.com/TuPagina`
