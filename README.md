# SimonSaysGame
Arduino: ecco come creare il Simon Says Game
In questo tutorial vedremo in che modo creare un gioco interattivo con Arduino.

Il gioco in questione è il “Simon Says”. Il gioco consiste nell’accensione casuale di vari LED. Tramite i bottoni si dovrà ripetere la sequenza di accensione dei LED. Man mano la sequenza diventerà più lunga. Il gioco terminerà nel momento in cui si indovinerà per 13 volte consecutive la sequenza oppure quando la sequenza inserita non è quella esatta, in quest’ultimo caso vi sarà la possibilità di ricominciare il gioco nuovamente dall’inizio . Ci sarà un intervallo di tempo nel quale sarà possibile premere i bottoni. Superato tale intervallo il gioco terminerà.

Lo scopo del gioco, è riuscire a ricordare la sequenza di accensione corretta dei LED (decisa da Arduino) per il maggior numero di turni.

Si possono riscontare vari problemi nella costruzione del circuito. Per esempio pulsanti molti piccoli non sempre si posizionano correttamente. Un’altro possibile grattacapo può consistere nel cablaggio oppure in qualche LED mal funzionante.

Il tutto sarà accompagnato dalla riproduzione musicale da parte di un cicalino.

Ecco un video che illustra il funzionamento:
https://www.youtube.com/watch?v=FT8f8qMB4Ok

I materiali da utilizzare sono i seguenti:
Board di Arduino Uno o compatibili
4x LED
4X resistori da 220 ohm
4X bottoni
1x buzzer
Jumpers
1X BreadBoard
Il diagramma di collegamento è il seguente:
![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2020/03/Senza-titolo.png?resize=768%2C555&ssl=1)

In seguito un riepilogo del diagramma elettrico:
Bottone LED verde collegato al pin digitale 2
LED verde collegato al pin digitale 3
Buzzer collegato al pin digitale 4 e 7
LED giallo collegato al pin digitale 5
Bottone LED giallo collegato al pin digitale 6
Bottone LED rosso collegato al pin digitale 9
LED rosso collegato al pin digitale 10
Bottone LED blu collegato al pin digitale 12
LED blu collegato al pin digitale 13
 
Codice https://github.com/SimoneMoreWare/SimonSaysGame/blob/main/SimonsSaysGame.ino

Lo sketch è abbastanza lungo e complesso. Una volta caricato il codice sulla propria board di Arduino occorrea ttendere qualche secondo pre garantire una corretta compilazione. Poi si potrà iniziare a giocare.
