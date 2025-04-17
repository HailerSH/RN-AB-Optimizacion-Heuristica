# Trabajo 01: Optimización Heurística

**Docente:** Juan David Ospina Arango

**Estudiantes:**
- Hailer Serna Hernández
- Juan Jose Correa Hurtado
- Jacobo Ochoa Ramirez

📅 **Fecha de entrega:** 2 de mayo, 23:59

---

## Parte 1: Optimización Numérica

Considere las siguientes funciones de prueba:

- [Función de Rosenbrock](https://en.wikipedia.org/wiki/Rosenbrock_function)
- [Función de Rastrigin](https://en.wikipedia.org/wiki/Rastrigin_function)
- [Función de Schwefel](http://benchmarkfcns.xyz/benchmarkfcns/schwefelfcn.html)
- [Función de Griewank](http://benchmarkfcns.xyz/benchmarkfcns/griewankfcn.html)
- [Función Goldstein-Price](https://www.sfu.ca/~ssurjano/goldpr.html)
- [Función de las seis jorobas de camello (Three-Hump Camel)](https://www.sfu.ca/~ssurjano/camel3.html)

### Instrucciones

1. **Seleccione dos funciones de prueba.**
2. **Optimice las funciones en dos y tres dimensiones** usando:
   - Un método de descenso por gradiente con condición inicial aleatoria.
3. **Optimice las funciones en dos y tres dimensiones** usando:
   - Algoritmos evolutivos  
   - Optimización por enjambre de partículas (PSO)  
   - Evolución diferencial
4. **Visualización**  
   Genere un **GIF animado o video** del proceso de optimización:
   - Por descenso por gradiente.
   - Usando al menos un método heurístico.

### Discusión

Analice y compare:

- ¿Qué aportaron los métodos de descenso por gradiente?
- ¿Qué aportaron los métodos heurísticos?

Considere:

- El valor final de la función objetivo.
- El número de evaluaciones de la función objetivo.  
(Es posible que deba realizar varias corridas para obtener conclusiones significativas).

---

## Parte 2: Optimización Combinatoria

Un vendedor debe recorrer las 13 ciudades principales de Colombia.

### Tarea

- **Algoritmos a usar**:  
  - Colonias de hormigas (ACO)  
  - Algoritmos genéticos (GA)

- **Costo de desplazamiento**:  
  El costo total incluye:
  - Valor por hora del vendedor (parámetro a estudiar)
  - Costo de peajes
  - Costo de combustible (según el vehículo elegido por el equipo)

- **Visualización**:  
  Representar con un **GIF o video** el mejor recorrido encontrado, sobre un **mapa de Colombia**.

---

## Reporte Técnico

Debe incluir:

- **Entendimiento desarrollado**
- **Metodología** (justificada)
- **Bibliografía** (normas APA)
- **Gráficos y tablas** (rotulados y citados)
- **Publicación**:  
  Publicar el reporte como una **entrada de blog**

### Reporte de Contribución Individual

Incluir una sección como la siguiente:

```text
+ Juan Pérez: programación del componente A, elaboración del reporte  
+ Maria Pérez: formato del reporte, elaboración de la animación X  
+ Diego Posada: selección de bibliografía, desarrollo de los componentes C y D, elaboración del reporte
