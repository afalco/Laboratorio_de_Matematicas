# Tres conjuntos de datos sintéticos para ejercicios de estadística

Los tres ficheros que se encuentran en este directorio contienen 140 observaciones. Son datos generados artificialmente. No proceden de muestras reales ni representan una encuesta real.

1. `Datos_estudiantes.csv`: Cada fila representa un estudiante ficticio.
    - `id`: identificador (cualitativa nominal/identificador; no usar como variable numérica de análisis).
    - `curso`: curso escolar (cualitativa ordinal).
    - `edad`: años (cuantitativa discreta).
    - `genero`: categoría declarada (cualitativa nominal).
    - `horas_estudio_semana`: horas por semana (cuantitativa continua).
    - `asistencia_pct`: porcentaje de asistencia (cuantitativa continua).
    - `horas_sueno_noche`: horas por noche (cuantitativa continua).
    - `horas_pantalla_dia`: horas de pantalla al día (cuantitativa continua).
    - `metodo_estudio`: método habitual (cualitativa nominal).
    - `dispositivo_principal`: dispositivo principal para estudiar (cualitativa nominal).
    - `nota_media`: calificación de 0 a 10 (cuantitativa; tratada como continua).

2. `Datos_movilidad_urbana.csv`: Cada fila representa un desplazamiento ficticio habitual de una persona.
    - `id`: identificador (no usar como variable numérica de análisis).
    - `medio_transporte`: medio principal (cualitativa nominal).
    - `distancia_km`: distancia aproximada (cuantitativa continua).
    - `tiempo_min`: duración aproximada (cuantitativa continua).
    - `coste_estimado_eur`: coste estimado por desplazamiento en euros (cuantitativa continua).
    - `motivo_desplazamiento`: motivo principal (cualitativa nominal).
    - `frecuencia`: frecuencia habitual (cualitativa ordinal).
    - `satisfaccion_1_10`: valoración de 1 a 10 (ordinal; a menudo se trata como cuantitativa discreta en ejercicios introductorios).

3. `Datos_perros.csv`: Cada fila representa un perro.
    - `id`: identificador (no usar como variable numérica de análisis).
    - `raza`: raza del perro (cualitativa nominal).
    - `peso`: peso (cuantitativa continua).
    - `habitat`: interior o exterior (cualitativa nominal).
    - `esteril`: recoge si el perro es estéril o no (cualitativa dicotómica).
    - `hematopre`: porcentaje de hematocrito al inicio del estudio (cuantitativa continua).
    - `grasa`: porcentaje de grasa corporal (cuantitativa continua).
    - `hematopost`: porcentaje de hematocrñito al final del estudio (cuantitativa continua).
    - `leish`: seropositivo a *leishmaniosis* (cualitativa dicotómica).