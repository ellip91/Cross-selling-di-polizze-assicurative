**Progetto: Cross-selling di Polizze Assicurative**

Il cliente è una compagnia di assicurazioni che ha fornito un'assicurazione sanitaria ai suoi clienti e ha bisogno di costruire un modello predittivo 
in grado di prevedere se gli assicurati dell'anno passato potrebbero essere interessati ad acquistare anche un'assicurazione per il proprio veicolo.

Il dataset (insurance_cross_sell.cvs) è composto dalle seguenti proprietà:

id: id univoco dell'acquirente.
Gender: sesso dell'acquirente.
Age: età dell'acquirente.
Driving_License: 1 se l'utente ha la patente di guida, 0 altrimenti.
Region_Code: codice univoco della regione dell'acquirente.
Previously_Insured: 1 se l'utente ha già un veicolo assicurato, 0 altrimenti.
Vehicle_Age: età del veicolo
Vehicle_Damage: 1 se l'utente ha danneggiato il veicolo in passato, 0 altrimenti.
Annual_Premium: la cifra che l'utente deve pagare come premio durante l'anno.
Policy_Sales_Channel: codice anonimizzato del canale utilizzato per la proposta (es. per email, per telefono, di persona, ecc...)
Vintage: numero di giorni dalla quale l'utente è cliente dell'azienda.
Response: 1 se l'acquirente ha risposto positivamente alla proposta di vendita, 0 altrimenti.


Al fine di prevedere il valore di Response, 
