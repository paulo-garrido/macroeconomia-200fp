# El capital sigue al riesgo

Presentación editable en Quarto, con 14 diapositivas en español. Tiempo orientativo: 12–15 minutos, más discusión.

## Abrir y presentar

Abre `mapeo-etapa-riesgo.html` en Chrome, Edge o Firefox. Mantén la carpeta `assets` junto al HTML para abrir las tres láminas originales. La presentación y sus interacciones funcionan sin conexión; los enlaces a Y Combinator requieren Internet. Los PDF de respaldo se abren desde la carpeta hermana `Tareas` incluida en el paquete.

- Flechas derecha e izquierda: avanzar y regresar.
- `Esc`: vista general de las diapositivas.
- `F`: pantalla completa.
- `?`: ayuda del navegador de diapositivas.

En la diapositiva 3, selecciona A, B o C y abre la lámina de clase. En la 11, mueve el control para explorar la caída de caja. En la 13, selecciona una respuesta para abrir la discusión.

## Editar

- `mapeo-etapa-riesgo.qmd`: contenido.
- `assets/theme.css`: tipografía, colores y composición.
- `assets/interactions.html`: comportamiento de fases, imágenes, simulación y pregunta.
- `assets/fase-1.jpeg`, `fase-2.jpeg`, `fase-3.jpeg`: imágenes originales completas.

Para regenerar desde la raíz del proyecto:

```sh
quarto render presentacion/mapeo-etapa-riesgo.qmd
```

El HTML contiene los estilos y las bibliotecas de la presentación. Las láminas que se abren con botones se mantienen como archivos locales.

## Base académica

Se usan las instrucciones de la tarea, el análisis previo de Stefani Villeda y Paulo Garrido y las tres imágenes de clase. Las diapositivas distinguen el instrumento de su financiador: participación accionaria / ángel; SAFE / VC temprano; crédito a plazo / banco. La diferencia entre SAFE y nota convertible se apoya en documentación de Y Combinator, enlazada en la presentación.

Las recomendaciones se condicionan a los datos disponibles. No se inventan montos, valoraciones, garantías o métricas de los casos. Los valores del simulador son supuestos didácticos explícitos y la pregunta de discusión introduce un escenario hipotético adicional.

## Orden narrativo

1. Portada.
2. Criterio etapa → riesgo → instrumento → actor.
3. Cadena de financiamiento interactiva.
4–5. Fintech: propuesta y riesgos de ambas partes.
6–8. SaaS: propuesta, precisión SAFE/nota y riesgos.
9–10. AgriTech: propuesta y riesgos.
11. Prueba de caja interactiva.
12. Comparación transversal.
13. Discusión con respuesta interactiva.
14. Conclusión.


Se retiraron los pies de referencia, las notas del expositor y la diapositiva de fuentes. La documentación técnica del SAFE permanece identificada aquí: https://www.ycombinator.com/documents/ . Los documentos de trabajo propios no se presentan como material entregado por la profesora.
