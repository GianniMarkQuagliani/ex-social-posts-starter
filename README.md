# Social Posts
- Creiamo il nostro array di oggetti post
- Stampiamo i post del nostro feed
- Funzione per creare un elemento HTML per rappresentare un post
- Creo un nuovo elemento div per rappresentare un post
- Creo l'intestazione del post
- Creo un elemento per contenere i metadati del post come autore e data
- Creo un elemento per l'icona del profilo dell'autore
- Creo un elemento img per l'immagine del profilo dell'autore
- Collego l'immagine del profilo all'elemento dell'icona
- Creo un elemento per i metadati dell'autore e della data
- Creo un elemento per il nome dell'autore
- Creo un elemento per la data del post (es. "4 mesi fa")
- Calcolo della data effettiva
- Collego il nome dell'autore e la data ai metadati
- Collego l'icona del profilo e i metadati all'elemento dei metadati
- Collego i metadati all'intestazione del post
- Creo un elemento per il testo del post
- Creo un elemento per l'immagine del post
- Creo un elemento img per l'immagine del post
- Collego l'immagine del post all'elemento dell'immagine
- Creo un elemento per il footer del post
- Collego tutti gli elementi creati al post completo
- Restituisci l'elemento del post completo
- Iteriamo attraverso l'array di post e creiamo gli elementi HTML per ciascun post

# Mi piace
- Creo un elemento per il pulsante "Mi Piace"
- Creo un link per il pulsante "Mi Piace"
- Creo un'icona per il pulsante "Mi Piace"
- Creo un'etichetta per il pulsante "Mi Piace"
- Collego l'icona e l'etichetta al pulsante "Mi Piace"
- Collego il pulsante "Mi Piace" al suo contenitore
- Creo un elemento per visualizzare il conteggio dei Mi Piace
- Collego il pulsante "Mi Piace" e il conteggio al contenitore dei "Mi Piace"
- Collego il contenitore dei "Mi Piace" al footer del post

# Gestiamo il click sul pulsante "Mi Piace"
- Seleziono tutti i pulsanti "Mi Piace" utilizzando la classe ".js-like-button"
- Iteriamo attraverso tutti i pulsanti "Mi Piace"
- Aggiungo un listener per il click su ciascun pulsante
- Gestisco il comportamento predefinito del link (evita che la pagina venga ricaricata)
- Verifico se l'ID del post è già presente nell'array dei post "Mi Piace"
- Creo un array per tenere traccia degli ID dei post a cui è stato messo "Mi Piace"
- Se l'ID del post non è presente, lo aggiungo all'array
- Aggiungo la classe "like-button--liked" al pulsante per cambiare il suo aspetto
- Trovo l'elemento del conteggio dei "Mi Piace" corrispondente a questo post
- Ottengo il numero corrente di "Mi Piace" dal contenuto dell'elemento
- Incremento il conteggio di "Mi Piace" di 1 e aggiorniamo il testo nell'elemento