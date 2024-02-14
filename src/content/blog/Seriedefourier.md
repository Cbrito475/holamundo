---
title: 'Series de Fourier y Transformada de Fourier'
description: 'Un vistazo a la series de Fourier y Transformada de Fourier.'
pubDate: 'Feb 13 2024'
heroImage: '/furier.jpg'
---

## Serie de Fourier

Las series de Fourier son una herramienta matemática que permite representar funciones periódicas como una suma de funciones sinusoidales. La idea básica es que cualquier función periódica puede descomponerse en una serie de ondas sinusoidales de diferentes frecuencias y amplitudes.<br>
La forma general de una serie de Fourier es:<br>
f(x) = a_0 + Σ (a_n cos(nπx/L) + b_n sin(nπx/L))
donde:<br>
•	f(x) es la función periódica que se desea representar<br>
•	a_0 es la constante de Fourier<br>
•	a_n y b_n son los coeficientes de Fourier<br>
•	L es el período de la función<br>
Los coeficientes de Fourier se pueden calcular mediante las siguientes fórmulas:<br>
a_0 = (1/L) ∫_0^L f(x) dx<br>
a_n = (2/L) ∫_0^L f(x) cos(nπx/L) dx<br>
b_n = (2/L) ∫_0^L f(x) sin(nπx/L) dx<br>

### Transformada de Fourier

La transformada de Fourier es una herramienta matemática similar a la serie de Fourier, pero que se aplica a funciones no periódicas. La transformada de Fourier descompone una función en una suma de ondas sinusoidales de diferentes frecuencias y amplitudes, pero no hay restricción en el período de la función.<br>
La forma general de la transformada de Fourier es:<br>
F(ω) = ∫_(-∞)^∞ f(x) e^(-jωx) dx
donde:<br>
•	F(ω) es la transformada de Fourier de f(x)<br>
•	ω es la frecuencia<br>
•	j es la unidad imaginaria<br>
La transformada inversa de Fourier se utiliza para obtener la función original a partir de su transformada de Fourier:<br>
f(x) = (1/2π) ∫_(-∞)^∞ F(ω) e^(jωx) dω<br>


### Relación entre la serie de Fourier y la transformada de Fourier

La serie de Fourier es un caso particular de la transformada de Fourier. La transformada de Fourier de una función periódica es una serie de deltas de Dirac, y la serie de Fourier es la suma de estas deltas de Dirac.

### Aplicaciones

Las series de Fourier y la transformada de Fourier se utilizan en una amplia gama de aplicaciones, como:<br>
•	Análisis de señales<br>
•	Procesamiento de imágenes<br>
•	Telecomunicaciones<br>
•	Sismología<br>
•	Ingeniería mecánica<br>
•	Física<br>
•	Matemáticas<br>

### Ejemplos

Algunos ejemplos de aplicaciones de las series de Fourier y la transformada de Fourier son:<br>
•	Filtrado de señales<br>
•	Compresión de imágenes<br>
•	Modulación de señales<br>
•	Detección de objetos en imágenes<br>
•	Análisis de vibraciones<br>
•	Resolución de ecuaciones diferenciales<br>
•	Estudio de la frecuencia de la luz<br>
