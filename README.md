[![LaTeX Build and Release](https://github.com/kanopo/vehicular-communications/actions/workflows/release.yaml/badge.svg)](https://github.com/kanopo/vehicular-communications/actions/workflows/release.yaml)

# Comunicazioni Veicolari (V2X) - Appunti del Corso

Il corso si propone d'introdurre lo studente alle comunicazioni veicolari,
fornendo le basi delle comunicazioni e delle reti per comprendere e progettare
sistemi di comunicazione vehicle-to-everything (V2X).

Non sono richiesti prerequisiti per seguire il corso. Tuttavia, può essere
utile aver frequentato corsi base di telecomunicazioni e di programmazione.

## Contenuto della Repository

Questa repository contiene gli appunti del corso di Comunicazioni Veicolari in
formato LaTeX. Gli argomenti trattati spaziano dalle nozioni fondamentali di
rete e comunicazione fino agli aspetti più tecnici e specifici dei sistemi V2X.

## Struttura degli Appunti

Gli appunti sono suddivisi in fili imitando le dispense consegnate dai docenti
durante le spiegazioni.

## Come Utilizzare

La repository è configurata in modo da generare il documento PDF ogni volta che
si pubblica su GitHub il lavoro svolto in locale.

Per lo sviluppo locale consiglio l'estensione di VS Code chiamata LaTeX Workshop
oppure l'utilizzo dalla CLI mediante il comando che segue:

`bash latexmk -pvc -pdf main.tex latexmk -c `

Il primo comando serve a generare iterativamente il documento PDF, il flag
`-pvc` permetta la generazione a ogni salvataggio dei documenti modificati e
`-pdf` serve a specificare la tipologia di documento oche si vuole generare.

Il secondo comando serve a eliminare dalla cartella tutti i file ausiliari
generati durante la compilazione di LaTeX.

Per lo sviluppo locale utilizzo per comodità:

`bash latexmk -pvc -pdf main.tex; latexmk -c `

## Contribuire

Se desideri contribuire al miglioramento e all'aggiornamento degli appunti,
sentiti libero di fare una pull request con le tue modifiche o aggiunte.

## Licenza

Questi appunti sono distribuiti sotto la licenza GNU General Public License
v3.0 (GPL-3.0), che consente la condivisione e l'adattamento degli appunti per
qualsiasi uso, a condizione che venga data attribuzione all'autore originale e
che le modifiche vengano distribuite con la stessa licenza. Per maggiori
dettagli, consulta il file LICENSE incluso in questa repository.
