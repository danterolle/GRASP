# Creator

Questo pattern assegna la responsabilità della creazione di un oggetto a un altro oggetto che ha una conoscenza specifica dei requisiti per creare un'istanza appropriata. Ad esempio, in un sistema di prenotazione alberghiera, la responsabilità di creare una nuova prenotazione potrebbe essere assegnata alla classe "Sistema di prenotazione", che ha la conoscenza delle disponibilità delle camere e delle tariffe. Questo pattern rende il codice più flessibile e facile da mantenere, poiché le modifiche alle regole di creazione vengono gestite in un unico punto.
