# Analysis RNA-seq Gene Expression

![RNA-Seq Banner](https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/RNA-Seq-alignment.png/800px-RNA-Seq-alignment.png)

## Descripción

El propósito de este proyecto es analizar la expresión génica a través del uso de datos de secuenciación de ARN (RNA-Seq). Este repositorio provee los scripts y la estructura necesaria para reproducir el análisis computacional desde los datos crudos hasta los conteos de expresión.

## Objetivos

- Procesar datos crudos de RNA-Seq.
- Realizar control de calidad de las lecturas.
- Alinear las lecturas y analizar la expresión génica diferencial.
- Generar visualizaciones y resultados completamente reproducibles.

## Estructura del repositorio

| Carpeta       | Descripción                                      |
|---------------|--------------------------------------------------|
| `data/`       | Datos de entrada (archivos FASTQ, referencias)   |
| `scripts/`    | Scripts de análisis y pipelines                  |
| `results/`    | Resultados generados (conteo, gráficas)          |
| `notebooks/`  | Análisis exploratorio interactivo (Jupyter)      |
| `docs/`       | Documentación adicional del proyecto             |

## Requisitos

Para ejecutar este proyecto, necesitarás instalar las siguientes herramientas:

- [Python](https://www.python.org/) 3.x
- [R](https://www.r-project.org/)
- [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
- [STAR](https://github.com/alexdobin/STAR) aligner

## Instrucciones de Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/Analysis_RNAseq_gene_expression.git
   cd Analysis_RNAseq_gene_expression
   ```
2. **Prepara los datos:**
   Coloca tus archivos de lectura rápida (`.fastq`) en el directorio `data/`.
3. **Ejecuta el control de calidad:**
   Accede a la carpeta `scripts/` y ejecuta el script correspondiente.
   ```bash
   bash scripts/01_quality_control.sh
   ```
4. **Resultados:**
   Revisa los archivos generados dentro de la carpeta `results/`.

## Autores

**Diana Campoverde**
[Perfil de Diana](https://github.com/Diana081998)

**Ana Mejía**
[Perfil de Ana](https://github.com/anejia1992)
