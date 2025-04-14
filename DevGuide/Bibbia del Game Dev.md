In questa sezione troverete le regole da rispettare durante lo sviluppo del gioco così da non impazzire con refactoring continui e spaghetti code.

# Regola n. 1 - Organizzazione del Lavoro
Prima di iniziare a lavorare ad una funzione, chiedere sempre se qualcuno ci sta già lavorando. Così da non fare lavoro inutile. Per vedere le cose da fare esiste il sito **HacknPlan** dove sono scritte tutte le funzioni da sviluppare. Se non potete vedere il progetto su HacknPlan chiedete ai moderatori di farvi aggiungere.

# Regola n. 2 - Version Control
Per il version control del progetto useremo il nostro grande dio GIT.
Attieniti alle seguenti sotto-regole per non trovarti davanti chilometri e chilometri di conflitti ad ogni commit.
## Regola 2.1 - Per ogni feature creare un branch
Il branching system da noi scelto è il seguente:

main
	dev
		**funzione**

Se devi fare una funzione che richiede la preesistenza di un'altra funzione che non è ancora stata inglobata su **dev** crea un branch che deriva da quella funzione (se potete comunicatelo così magari ci organizziamo con i pull).
## Regola 2.2 - Mai committare sul branch Main
Mai e poi mai committare sul branch main in quanto è dove c'è la parte di codice funzionante. Ogni milestone si fa il merge su Dev e poi, dopo aver testato a sufficienza, si effettua il merge con il main.

# Regola 3 - Seguite lo schema dello Scene tree
Seguite lo scene tree descritto [qui](Scene%20Tree.md).

# Regola 4 - Seguite lo schema del File System
[Qui](File%20System.md) potete trovare lo schema del File System

# Regola 5 - 🐍🏡snake_case🐍🏡
Usate lo snake case (🐍🏡) per scrivere i nomi delle variabili.
Se non sapete cos'è lo snake case, questa è la differenza tra snake case e camel case:
- snake_case
- CamelCase
# Regola 6 - Estendete le classi
Se dovete fare una modifica ad una classe o ad uno script cercate di estenderlo.
In questo modo ci saranno meno conflitti nel codice durante i merge e soprattutto meno errori in caso di modifiche.

# Regola 7 - NON modificate gli Addon
Se scaricate una libreria e dovete apportare una modifica, non modificatela direttamente ma create uno script e fategli ereditare la libreria ed implementate le modifiche.

# Regola 8 - Per qualsiasi dubbio chiedete
Se avete qualche dubbio riguardante il progetto oppure come fare una determinata cosa, chiedete sul discord e tutto si risolverà😎.

# Regola 9 - Tubozzi

# Regola 10 - Buon Lavoro 🧑‍💻
Complimenti hai letto tutte e 10 le regole del bravo Game Dev ora sei pronto a gettarti nell'apocalittico mondo di Silicon Valley!
