---
# Metadati della presentazione (YAML header)
title: "La Mia Presentazione"
subtitle: "Un sottotitolo interessante"
# author: 
#  - Giulio Romano De Mattia
#  - Pietro Barale
institute: MEduLab
date: \today
# Opzioni Beamer
theme: default
colortheme: default
aspectratio: 169          # 16:9 (usa 43 per 4:3)
navigation: empty         # nascondi simboli navigazione
section-titles: true      # slide per ogni sezione
# Altre opzioni utili
toc: false                 # indice
toc-title: "Contenuti"
fontsize: 10pt
lang: it
colorlinks: true
---

# Introduzione

## Prima Slide

Questo è un esempio di testo nella prima slide.

- Punto elenco 1
- Punto elenco 2
- Punto elenco 3

## Slide con Codice

Ecco un esempio di codice:

```python
def saluta(nome):
    return f"Ciao {nome}!"

print(saluta("Mondo"))
```

# Sezione Principale

## Slide con Formula

L'equazione di Einstein:

$$E = mc^2$$

Oppure inline: $a^2 + b^2 = c^2$

## Slide con Immagine

![Didascalia dell'immagine](docs/assets/images/immagine.png){width=70%}

## Slide con Spartito

| Colonna 1 | Colonna 2 | Colonna 3 |
|-----------|-----------|-----------|
| A         | B         | C         |
| 1         | 2         | 3         |
| X         | Y         | Z         |


![Didascalia dell'immagine](docs/assets/music/frammento.pdf){width=20%}



## Slide con Tabella

| Colonna 1 | Colonna 2 | Colonna 3 |
|-----------|-----------|-----------|
| A         | B         | C         |
| 1         | 2         | 3         |
| X         | Y         | Z         |

# Conclusioni

## Ultima Slide

- Punto chiave 1
- Punto chiave 2
- Punto chiave 3

**Grazie per l'attenzione!**

## Slide con Due Colonne

:::::: {.columns}
::: {.column width="50%"}

**Colonna Sinistra**

- Punto A
- Punto B

:::
::: {.column width="50%"}

**Colonna Destra**

- Punto 1
- Punto 2

:::
::::::
