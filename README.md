# AltaCV - CV in LaTeX a Singola Pagina 

v1.0 (25 Gennaio 2024) di Calogero Gioacchino Corsello

[Per la versione inglese Clicca Qui](https://github.com/Kalos99/LaTeX_resume/tree/ENG)
## Introduzione

Questo repository è pensato per te che vuoi creare o aggiornare il tuo curriculum vitae in modo interessante e innovativo utilizzando LaTex.
Tramite il modello e  seguendo i passaggi di seguito mostrati ti sarà possibile in pochi minuti creare il tuo curriculum personale. Buon divertimento!

Per qualsiasi domanda puoi scrivermi a [calogerocorsello1999@gmail.com](mailto:calogerocorsello1999@gmail.com).

Puoi trovarmi anche su:

[![tech-fusiom.it](https://github.com/EmanueleSeminara/images/blob/main/LinkedIn_icon_2x20.png?raw=true)](https://www.linkedin.com/in/emanuele-seminara/)
[![tech-fusion.it](https://github.com/EmanueleSeminara/images/blob/main/Instagram_icon_20x20.png?raw=true)](https://www.instagram.com/emanuele_seminara/)
[![tech-fusion.it](https://github.com/EmanueleSeminara/images/blob/main/pulsante_tech_fusion_20x20.png?raw=true)](https://tech-fusion.it/)

## Aspetto del Curriculum
![tech-fusion.it](./Calogero_Corsello_CV_ITA.jpg)

## Editor
Nel caso tu non conosca LaTeX, non preoccuparti, puoi utilizzare [Overleaf](https://overleaf.com), un editor online gratuito e fantastico,
basta creare un account, avviare un nuovo progetto e caricare i file di questo repository.

Per avere i file sul tuo PC, clona semplicemente questo repository:

1) Seleziona la posizione in cui desideri memorizzare il file nel tuo terminale

   ```bash
   cd Progetti/curriculum
   ```

2) Clona il repository

   ```bash
   git clone https://github.com/Kalos99/LaTeX_resume.git
   ```

Dopo aver caricato i file, dovrai solo modificare il contenuto dei file per scrivere ciò che desideri nel tuo curriculum.
È davvero intuitivo, nel caso tu abbia bisogno di ulteriori informazioni su cosa modificare, puoi consultare le sezioni seguenti.

## Requisiti e Compilazione

* Alla riga 76 di main.tex puoi inserire le tue informazioni personali.
* page1sidebar.tex contiene il codice per la parte destra del curriculum.
* Ricorda di sostituire l'immagine con la tua foto e utilizza un formato png.
* Se desideri cambiare i colori, vai alla riga 48 di main.tex.
* AltaCV utilizza [`fontawesome`](http://www.ctan.org/pkg/fontawesome) e [`academicons`](http://www.ctan.org/pkg/academicons); sono inclusi sia in TeX Live 2016 che in MikTeX 2.9.
* Il caricamento di `academicons` è facoltativo: attivalo aggiungendo l'opzione `academicons` a `\documentclass`.
* Ora può essere compilato con pdflatex, XeLaTeX e LuaLaTeX!
* Tuttavia, se stai utilizzando `academicons`, _devi_ usare XeLaTeX o LuaLaTeX. Se il documento viene compilato ma le icone non appaiono nel PDF finale, prova a compilare con LuaLaTeX invece.
* Negli esempi qui mostrati viene utilizzato il carattere [Lato](http://www.latofonts.com/lato-free-fonts/).