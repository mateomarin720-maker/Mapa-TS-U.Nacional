# Mapa de Revistas Latinoamericanas de Trabajo Social

Mapa interactivo de las revistas inscritas y asistentes a la feria de revistas de ALAEITS, para la revista *Trabajo Social* de la Universidad Nacional de Colombia.

**Ver el mapa:** https://mateomarin720-maker.github.io/Mapa-TS-U.Nacional/

## Cómo actualizar las revistas

1. Abre `index.html` y pulsa el lápiz (Edit).
2. Busca la sección `// ===== DATOS =====`.
3. Copia una línea `{ ... }` dentro de `"inscritos"` o `"asistentes"` y cambia sus valores:
   - `pais`, `ciudad`, `revista`, `institucion`, `web`
   - `lat` y `lng`: coordenadas de la ciudad (en Google Maps, clic derecho sobre la ciudad y copia los números).
4. Pulsa **Commit changes**. El mapa se actualiza en 1 o 2 minutos.

## Insertar en OJS

```html
<iframe src="https://mateomarin720-maker.github.io/Mapa-TS-U.Nacional/"
        title="Mapa de Revistas Latinoamericanas de Trabajo Social"
        style="width:100%; height:780px; border:0; border-radius:8px;"
        loading="lazy"></iframe>
```

Fuente de los datos: hoja "3.1. Revistas Latinoamericanas de Trabajo Social - Página web ALAEITS".
