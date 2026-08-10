# CalorIA — Fase 1

Aplicación web/PWA estática para estimar calorías a partir de una fotografía.

## Publicación con Netlify Drop
1. Descomprime este ZIP.
2. Entra en https://app.netlify.com/drop
3. Arrastra la carpeta `caloria_fase1` a la zona de Drop.
4. Netlify publicará la app en una URL `*.netlify.app`.

## iPhone
Abre la URL en Safari y usa Compartir → Añadir a pantalla de inicio.

## Qué hace esta fase
- Toma una fotografía o selecciona una imagen.
- Ejecuta un modelo de clasificación de alimentos en el navegador.
- No requiere API key ni servidor de IA.
- Estima kcal con una tabla inicial por alimento y una porción estándar de 250 g.

## Limitación deliberada
Esta fase identifica principalmente el alimento dominante. Todavía NO descompone de forma fiable un plato con varios alimentos ni conoce el peso real. Eso será Fase 2.

Modelo: onnx-community/swin-finetuned-food101-ONNX.
