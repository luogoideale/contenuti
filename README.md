# CND via GitHub

Per rendere più gestibile la gestione di alcuni contenuti, è possibile usare GitHub come CDN.

**Nota** una volta caricati i contenuti, le modifiche non sono immediate e solitamente sono richiesti alcuni minuti prima che siano visibili.

## Capacità attuali

In questa sezione sono elencati le attuali capacità del sistema, con i requisiti per un funzionamento corretto

### News

Le news vanno (guarda un po') in `news`, I file *devono* avere un nome nel formato `AAAAMMDD-HHMMSS.md`.
La data determina quando la news verrà pubblicata.
È possibile impostare date nel futuro per schedulare automaticamente la news.

Per creare una news, è necessario rispettare il seguente template:

 - prima riga, immagine;
 - riga vuota;
 - terza riga, titolo preceduto da ##;
 - riga vuota;
 - contenuto, su quante righe si desidera.

ad esempio

	![Fallback text](images/github/news/github.png)

	## News via GitHub

	È ora possibile pubblicare le news via [GitHub][1]!
	Questa notizia è **bellissima**!

	[1]: http://github.com

### Immagini

Le immagini possono essere caricate su GitHub nella directory `images`, ma per potervi accedere è necessario riferirsi a loro tramite l'indirizzo `images/github/*`.

Per linkare un'immagine che si trova su github in `images/foo.jpg`, bisogna riferirsi ad essa come `images/github/foo.jpg`.
