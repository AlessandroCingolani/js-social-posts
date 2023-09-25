#  Social Posts 


Ricreiamo un feed social aggiungendo al layout di base fornito, il nostro script JS in cui:

**Milestone 1** - Creiamo il nostro array di oggetti che rappresentano ciascun post.
Ogni post dovrà avere le informazioni necessarie per stampare la relativa card:
- id del post, numero progressivo da 1 a n
- nome autore,
- foto autore,
- data in formato americano (mm-gg-yyyy),
- testo del post,
- immagine (non tutti i post devono avere una immagine),
- numero di likes.

**Milestone 2** - Prendendo come riferimento il layout di esempio presente nell’html, stampiamo i post del nostro feed.

**Milestone 3** - Se clicchiamo sul tasto “Mi Piace” cambiamo il colore al testo del bottone e incrementiamo il counter dei likes relativo.
Salviamo in un secondo array gli id dei post ai quali abbiamo messo il like.

1. Creo array con oggetti informazioni richieste per poi stamparle dentro la card

2. Utilizzo date.now per prendere informazioni attuali della data del post

3. Elaboro dove mettere i dati forniti neln Html fornito 

4. Creo un contatore per i like , poi ricreo con filter quali non hanno valore zero e li metto nel mio array dei like.