# common-voice-tool
Common Voice Tool - CLI Tool <br>
GUI - Coming soon!<br>

[[Click here for the English Version]](README.md)

## Operazioni preliminari
**ULTIMA VERSIONE**
**BETA: v0.4.1**

Clona la repo:

```
git clone https://github.com/dag7dev/common-voice-tool
```

Se vuoi provare la beta:
```
git clone --single-branch -b beta https://github.com/dag7dev/common-voice-tool
```


## Versione BASH

```
cd common-voice-tool
cd bash
sudo chmod 755 common-voice-tool.sh
```

Ora potrai finalmente lanciare lo script!

## CLI
Se lanci lo script senza alcun parametro avrai la lista dei parametri che potrai inserire:
```
./common-voice-tool
utilizzo: ./common-voice-tool <options>
  -h or -help
    	Mostra questo messaggio
  -range or -chkLen
    	Controlla se la lunghezza della stringa è in un range.
  -trim
    	Elimina gli spazi bianchi ' ' alla fine di ogni riga.
  -chkPoint
      Controlla se ogni riga di un file termina con un punto (non lo sostituisce, controlla e basta!)
  -ac
      Aggiunge un punto se il file non termina con un punto.
  -noEmpty
      Elimina tutte le righe vuote.
  -capitalize
      Rende maiuscola la prima lettera di ogni frase.
```
Per lanciare questo script hai bisogno di lanciarlo con almeno un parametro.<br>
Ad esempio: 
```
./common-voice-tool -range
```
controllerà se la lunghezza di ogni riga è in un range.<br>

Non devi passare il nome del file sul quale andrai ad operare perché potrai selezionarlo una volta avviato lo script. <br>

Puoi lanciare lo script con più parametri per eseguire più operazioni.<br>
Esempio:
```
./common-voice-tool -range -noEmpty
```
controllerà se la lunghezza di ogni riga è in un range e rimuoverà le righe vuote.<br>

## LISTA PARAMETRI DISPONIBILI
Parametro | Cosa fa
------------ | -------------
-h | mostra la lista dei parametri disponibili (come se lanciassi lo script senza parametri).
-range | controlla la lunghezza di ogni riga del file
-chkLen | come sopra
-trim | Elimina gli spazi bianchi ' ' alla fine di ogni riga.
-chkPoint |  Controlla se ogni riga di un file termina con un punto.
-ac | Come sopra, ma in caso dovesse mancare aggiunge un punto.
-noEmpty | Elimina tutte le righe vuote.
-capitalize | Rende maiuscola la prima lettera di ogni frase.

## NOTE
Il tool è stato testato (dovreste quindi usarlo) SOLO con file di testo (txt o senza estensione se siete sotto Linux).
Puoi cambiare lingua selezionando il file contenuto nella cartella "lang".<br>
La cartella 'lang' deve sempre esistere e deve esserci sempre almeno un file per funzionare.

## Che branch devo usare?
La beta l'aggiorno spesso e non è stabile.<br>
La master ho deciso che finchè non uscirà una versione stabile della beta rimarrà così.<br>
Ti consiglierei di utilizzare la beta ;)

## WIP

Todo:
- Dividere le linee a partire da un testo automaticamente
- ~~Localizzazione -> traduzione in altre lingue~~ **FATTO**
- ~~Rendere tutte le iniziali delle frasi maiuscole~~ **FATTO**
- ~~Aggiungere il controllo dei caratteri prima di aggiungere un punto.~~ **FATTO**
- ~~Eliminare tutte le righe vuote.~~ **FATTO**

## Posso contattarti o avere un tuo recapito?
Certo! Trovi la mia email nei vari codici sorgente!<br>
Puoi anche contattarmi su GitHub se preferisci!<br>
Fammi sapere se questo software ti piace o se c'è qualcosa da sistemare!<br>

## Perchè questo tool?
Questo strumento è stato ideato per lavorare più velocemente con le stringhe di common-voice.<br>
Può aiutare a controllare la lunghezza di ogni stringa, aggiungere il punto ad ogni riga e molto altro.<br>

## In che modo posso aiutarti?
Dammi dei suggerimenti per migliorare o riporta dei bug e/o dei malfunzionamenti! :) <br>
(anche un semplice feedback può essere d'aiuto!) <br>
