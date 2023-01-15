# Flipper-Zero-BadUSB
Collezione al momento sperimentale di script per F0 BadUSB


-=BrowserWebMiner=-
Lo script si compone di 3 fasi:
1- creazione cartella webbe in Files di HOMEPATH
2- download dei file index e js 
3- esecuzione di chrome per apertura di index in background

Ovviamente il pc deve avere Chrome installato, lo script non viene rilevato da Defender ne dai maggiori agent EDR che ho potuto testare. Le opzioni, quali wallet pool porta % di utilizzo CPU ecc, sono da modificare nel file index. Consiglio quindi di scaricare prima l'index, modificarlo e sostituire la curl del mio index con il vostro. 

Se lo lanciate, per errore o per test, da come lo condivido per fermarlo dovete tramite il task manager ordinare per % di utilizzo cpu e eliminare il primo processo CMD, al momento l'index che viene scaricato è impostato per usare il 100%

La parte del miner viene da questo git (con le dovute modifiche):
https://github.com/sascha08-15/turtlecoin-web-miner


-=DisableDefender=-
Testato su pochi pc disabilita in parte o totalmente defender.



-=Enable_WinRM_Remote PS=-
Abilita WinRM e quindi l'esecuzione di ps da remoto



-=Linux_Base_Shell=-
Apre una shell su os linux (versione molto base)


-=Windows_ReverseShell=-
Apre una shell su os linux (versione molto base)


-=ShadowCopySAM_Dump=-
Se presenti delle copie di backup in shadow estrae da li il SAM file per le credenziali locali
