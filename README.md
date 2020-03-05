# webapp_musica_streaming
Progetto di sviluppo in team da svolgere nelle quinte informatica: applicazione web che simuli una piattaforma di musica in streaming.
La nostra applicazione non conterrà un riproduttore di musica: gli ascolti saranno simulati da una pagina che mostra  semplicemente un messaggio del tipo: "stai ascoltando ... di ...".

Gli utenti registrati possono ascoltare una serie di brani di vari artisti (che possono essere artisti singoli o gruppi). 
Ogni artista è associato a una serie di tag (che possono rappresentare il genere o altre classificazioni tipo "per studiare" o "grandi classici") che possono essere aggiunte dagli stessi utenti.
Il servizio utilizza le tag per consigliare agli utenti altri artisti collegati ai propri ascolti.
Un artista può essere collegato gli altri artisti anche senza che abbiano tag in comune, semplicemente perchè hanno collaborato o hanno suonato nella stessa band o anche perché un "artista" è in realtà una band e gli artisti collegati sono i membri di qella band.
Ogni utente può creare delle playlist che possono essere private o pubbliche.
Un utente può "seguire" un altro utente per ricevere notifiche ogni volta che pubblica o modifica una playlist.
Allo stesso modo, un utente può seguire un artista per essere notificato dei nuovi brani pubblicati. 
Gli utenti possono aggiungere i brani a una lista di brani preferiti.
Ogni brano è associato a una valutazione, che dipende dal numero di utenti che hanno inserito il brano tra i propri preferiti.
Per riprodurre la musica, l'applicazione deve conoscere il nome del file audio corrispondente ad ogni brano.
