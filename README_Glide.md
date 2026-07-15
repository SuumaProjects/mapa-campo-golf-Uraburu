# Mapa de Campo Uraburu - Glide + GitHub Pages

## Archivos
- `index.html`: archivo listo para subir a GitHub Pages.

## Repositorio recomendado
`mapa-campo-golf-uraburu`

## URL de prueba
```text
https://suumaprojects.github.io/mapa-campo-golf-uraburu/?lang=es&v=uraburu1
```

## URL para Glide
```text
https://suumaprojects.github.io/mapa-campo-golf-uraburu/?lang=User_Language&v=uraburu1
```

## Configuracion en Glide
- Usar Web Embed apuntando a la columna `URL_Mapa_Campo`.
- En la Template Column usar `lang=User_Language`, sin llaves.
- Replacement: `User_Language` -> columna real de idioma del usuario.
- No usar `loc=User_Location` en la pantalla real para evitar recarga/parpadeo del iframe.

## Puntos incluidos
- H1-H18 como `TEE`.
- H1 y H10 se destacaran automaticamente como inicio de vuelta.
- 2 puntos `WC`.
- Casa Club: `CLUBHOUSE`.
- Campo de Practicas: `PRACTICE`.

## Version
`v=uraburu1`

Cambiar el parametro `v=` cada vez que se actualice el `index.html` en GitHub para evitar cache.
