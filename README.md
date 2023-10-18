# Intelligenza-Artificiale-Soar-
Progetto di programmazione delle architetture cognitive

Il progetto consiste nell'implementazione di un agente che, trovandosi in una stanza senza via d'uscita e con solo una finestra a 3 metri di altezza, deve cercare di scappare.
L'agente ha attorno a se ha degli oggetti che dovrà imparare a combinare o a sfruttare per trovare una via di fuga.
La struttura dell'agente si basa su un Ciclo deliberativo, ovvero:
- OBSERVE, l'agente osserva l’ambiente ed elenca gli oggetti rilevanti e le loro posizioni;
- PLAN, l'agente formula un piano; ogni piano definisce quali oggetti usare, da quale posizione della stanza lanciare e il punto della finestra da colpire;
- EXECUTE, l'agente esegue le azioni pianificate.

Saranno poi utili l'implementazione di Scelte implementative e Sistema di Reward per portare a termine il compito


