Specificare e caricare un *dataset* di tipo Serie Temporale
-----------------------------------------------------------

Se si sta caricando un dataset di tipo ``Serie Temporale`` seguire i seguenti
passi aggiuntivi di configurazione:

#. Nel menu a *tendina* di selezione dedicato, scegliere tra le voci:

    #. ``“Time Series from a CSV file”``, qualora la serie temporale è presente 
    su uno dei file precedentemente caricati in formato ``CSV``; Il sistema	
    rileverà la presenza di una serie temporale all'interno di un file 
    di tipo *csv*.
    
    #. ``Time Series from TSDSystem (GUID required)``, verrà richiesto di 
    fornire un identifico *GUID* univoco precedentemente creato dall'istanza 
    ``TSDSystem`` (identifica una serie temporale già caricata precedentemente 
    sul database TSDSystem da associare a questo record).

#. Nel *form* successivo, è possibile specificare tutti i *metadati* aggiuntivi 
   necessari per la descrizione del *dataset* di tipo *Serie Temporale*; 
   questi dettagli sono necessari per la *preview* grafica sulla *landing page* 
   una volta che il dataset verrà pubblicato (vedi fase successiva validazione 
   scheda) sul portale OEDataRep.

.. warning::
   Requisito **mandatorio** per il corretto caricamento della serie temporale sul 
   backend del TSDSystem, è che la colonna contentente i ``“timestamp”`` 
   deve essere nominata "**time**".

.. image:: assets/pictures/ts_web_form.png
     :align: center
