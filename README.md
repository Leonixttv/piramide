# Piramide
Calcolo dell'altezza massima di una piramide
Questo programma in C# calcola l'altezza massima di una piramide data una certa quantità di cubi di pietra. Il programma considera una piramide compatta, senza cavità interne, con ogni piano quadrato e con una lunghezza laterale inferiore di due rispetto a quella sottostante. Inoltre, si assume che il primo piano sia costituito da un solo cubo di pietra.

Utilizzo
Il programma include due metodi per il calcolo dell'altezza della piramide e del numero di cubi di pietra rimanenti dopo la sua costruzione.

Per utilizzare il programma, è sufficiente eseguire il codice nel file Program.cs con un ambiente di sviluppo C# compatibile, come Visual Studio o Visual Studio Code.

All'interno del metodo Main, è possibile modificare il numero di cubi di pietra forniti per calcolare l'altezza massima della piramide e il numero di cubi di pietra rimanenti.

Metodi
Il programma include i seguenti due metodi:

int Piani(int mattoni)
Questo metodo calcola l'altezza massima della piramide data una certa quantità di cubi di pietra.

Argomenti:

mattoni: il numero di cubi di pietra disponibili per la costruzione della piramide.
Valore restituito:

Il metodo restituisce il numero di piani della piramide che possono essere costruiti con la quantità di cubi di pietra fornita.

int Rimanenti(int mattoni, int piani)
Questo metodo calcola il numero di cubi di pietra rimanenti dopo la costruzione della piramide.

Argomenti:

mattoni: il numero di cubi di pietra disponibili per la costruzione della piramide.
piani: il numero di piani della piramide costruiti.
Valore restituito:

Il metodo restituisce il numero di cubi di pietra rimanenti dopo la costruzione della piramide con la quantità di cubi di pietra e il numero di piani forniti.
