# coronavirus_diffusion

Questo progetto nasce dall'idea di avere grafici sull'andamento della diffusione del corona-virus in Italia. 

La base di partenza per l'analisi sono i dati della protezione civile, ma per enfatizzzare l'andamento del contagio, il numero dei casi positivi viene ponderato sul numero dei tamponi eseguiti, 
in modo da mettere in risalto la concentrazione dei casi positivi piuttosto che il numero assoluto.

Inoltre è possibile visualizzare i dati giornalieri e non i dati cumulati, così da percepire immediatamente un eventuale trend. 

Ovviamente, con i dati in possesso riguardanti una esigua parte della poplazione italiana, non si riesce ad avere il quadro della situazione nazionale. 

## Codice sorgente
Il codice contenuto nel repository coronavirus_diffusion è suddiviso in tre moduli:
- opendata_reader.py 
- matrix_builder.py
- chart_plotter.py

I grafici, al momento, sono di 3 tipi:

- timeline cumulativa
- timeline giornaliera
- media regionale

Il codice è scritto in Python3, usa le librerie numpy e matplotlib
