# Advanced Data Science Project

Questo repository contiene il report di analisi e la presentazione sviluppati per il progetto del corso di **Advanced Data Science**.

L'intero flusso di analisi e riproducibilità è implementato tramite **R Markdown** (`.Rmd`), da cui sono stati generati i documenti finali in formato HTML e PDF.

---

## 📂 Contenuto del Repository

* **`spotify.Rmd`** : File sorgente R Markdown contenente il codice R, i commenti e le visualizzazioni.
* **`spotify.html`**: Report interattivo completo generato da R Markdown.
* **`spotify.pdf`**: Versione stampabile / report formattato in PDF.
* **`presentation.pdf`**: Slide di presentazione del progetto.

---

## 📦 Download del Dataset

A causa dei limiti di dimensione imposti da GitHub per i file di grandi dimensioni, i dataset non sono inclusi direttamente nel repository.

I dati necessari per la riproduzione dell'analisi sono disponibili su Google Drive:

🔗 **[Scarica i Dataset da Google Drive](https://drive.google.com/drive/folders/1ir_7kVvGzvZUhj457dragw7UIdljMnCw?usp=drive_link)**

### Istruzioni per eseguire l'analisi:
1. Scarica i file dal link Google Drive.
2. Posiziona i file dei dati nella cartella del progetto (nella root).
3. Apri il file `.Rmd` in **RStudio** ed esegui il rendering cliccando su **Knit** (oppure esegui via console con `rmarkdown::render("spotify.Rmd")`).

---

## 🛠️ Requisiti Software

Per compilare ed eseguire il codice R Markdown sono richiesti:
* **R** (versione consigliata: >= 4.0)
* **RStudio** (consigliato)
* Pacchetti R principali:
  ```r
  library(tidyverse)
  library(igraph)      
  library(tidytext)     
  library(topicmodels)  
  library(corrplot)     
  library(knitr)        
  library(scales)       
  library(broom)        
  library(tinytex)
  ```
