# Appunti
Repository per organizzare i miei appunti

## Attenzione!

nessun appunto è ancora conenuto quì 

| ciao               | prova di tabella           |
| ------------------ | -------------------------- |
| cosi vediamo anche | come funzionano le tabelle |
| moolto bene        | pare                       |

sto solo provando come usare il markdown per scrivere testo formattato ***facilmente***

<br/><br/>

### Mermaid
usando meremaid è possibile creare dei diagrammi di vario tipo, tra cui questi comodi diagrammi di sequenze, per visualizzarlo potresti dover usare dei plugin

Diagramma "Three way Handshake"
```mermaid
sequenceDiagram
A->>B: SYN=1 ACK=0 sn=5000 an=?
B->>A: SYN=1 ACK=1 sn=1000 an=5001
A->>B: SYN=0 ACK=1 sn=5001 an=1001 l=500
B->>A: ACK=1 sn=1001 an=5501
```
