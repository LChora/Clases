# Clases
Un repositorio para recursos para mis estudiantes de Biología computacional de la Facultad de Ciencias UNAM
Este incluye recursos para usar en R, la forma de descargar los archivos directamente es así:

# Carga de datos desde las url
library(tidyverse)
datae <- read_tsv("https://raw.githubusercontent.com/LChora/Clases/refs/heads/main/mediciones_estudiantes.tsv", show_col_types = FALSE)
datab <- read_tsv("https://raw.githubusercontent.com/LChora/Clases/refs/heads/main/body_measures.tsv", show_col_types = FALSE)
