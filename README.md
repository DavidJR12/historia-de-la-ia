# Historia de la inteligencia artificial

Web divulgativa de una sola página: de la pregunta de Turing (1950) a los modelos
frontera de octubre de 2026, y lo que puede venir después.

**Ver la web:** https://davidjr12.github.io/historia-de-la-ia/

## Qué hay dentro

- **Cronología** 1950–2011: Turing, Dartmouth, el perceptrón, ELIZA, los dos inviernos,
  Deep Blue.
- **La explosión** 2012–2024: AlexNet, AlphaGo, el transformer, ChatGPT, el premio Nobel.
- **La era de los agentes** 2025–2026: modelos de razonamiento, agentes y la cadencia
  mensual de lanzamientos, con fechas verificadas en openai.com y anthropic.com.
- **Dónde estamos hoy** (19/10/2026) y una sección de **prospectiva** marcada como tal.

## Cómo está hecho

- `index.html`: todo el sitio (HTML, CSS y JavaScript) en un único archivo, sin
  dependencias ni CDN. Funciona abierto directamente desde el disco.
- `img/`: 10 fotografías de Wikimedia Commons, todas de dominio público o con licencia
  Creative Commons. La autoría y el enlace a cada ficha original están en la sección
  *Créditos y fuentes* de la web y en `img/creditos.json`.
- Transiciones al hacer scroll con `IntersectionObserver`, contadores animados y una
  línea de tiempo que se rellena. Si el navegador pide reducir movimiento, se desactivan.

## Uso local

Descarga el repositorio y abre `index.html` en el navegador. No hace falta servidor.

## Actualizar el despliegue

GitHub Pages sirve la rama `main` directamente, así que basta con:

```
git add -A
git commit -m "lo que cambies"
git push
```

En un minuto estarán los cambios publicados.

## Aviso

Los hechos históricos están fechados y contrastados. La sección final (lo que viene) es
prospectiva: tendencias y debate, no anuncios.

La web es de circulación privada: incluye `robots.txt` y etiquetas `noindex` para que los
buscadores no la listen. No es una barrera de acceso: cualquiera que tenga el enlace puede
verla.
