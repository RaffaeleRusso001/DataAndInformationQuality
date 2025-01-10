
# Dataset: Esercizi Storici - Analisi Qualità Dati

## Descrizione del Progetto

Questo dataset contiene informazioni relative agli esercizi storici, inclusi dettagli come l'ubicazione, la tipologia e altre caratteristiche specifiche. Il dataset è stato sottoposto a un processo di miglioramento della qualità dei dati, con un'analisi approfondita delle dimensioni della qualità, tra cui completezza, unicità, costanza e allineamento dello schema.

---

## Struttura del Dataset

Il dataset finale è composto da **6812 righe** e **16 colonne**:

| Colonna                                           | Tipo       | Descrizione                                                                                      |
|--------------------------------------------------|------------|--------------------------------------------------------------------------------------------------|
| `Tipo_esercizio_storico_pe`                      | Stringa    | Categoria dell'esercizio storico.                                                               |
| `Insegna`                                        | Stringa    | Nome dell'esercizio.                                                                             |
| `Tipo_via`                                       | Stringa    | Tipologia della via (es. "via", "piazza", ecc.).                                                 |
| `Descrizione_via`                                | Stringa    | Nome della via.                                                                                 |
| `Civico`                                         | Stringa    | Numero civico.                                                                                  |
| `Codice_via`                                     | Stringa    | Codice identificativo della via.                                                                |
| `ZD`                                             | Intero     | Zona demografica associata.                                                                     |
| `Forma_vendita`                                  | Stringa    | Modalità di vendita (es. somministrazione, dettaglio, ecc.).                                     |
| `Settore_storico_pe`                             | Stringa    | Settore di appartenenza dell'esercizio storico.                                                 |
| `Superficie_somministrazione`                    | Float      | Superficie dedicata alla somministrazione in metri quadrati.                                    |
| `Isolato`                                        | Intero     | Codice dell'isolato di appartenenza.                                                            |
| `Forma_commercio_solo_somministrazione_boolean`  | Booleano   | Indica se è presente solo somministrazione.                                                     |
| `Forma_commercio_somministrazione/minuto_boolean`| Booleano   | Indica se è presente somministrazione e vendita al minuto.                                      |
| `Forma_commercio_prev_somministrazione_boolean`  | Booleano   | Indica se è previsto il commercio con somministrazione.                                         |
| `Forma_commercio_prev_minuto_boolean`            | Booleano   | Indica se è previsto il commercio al minuto.                                                   |
| `Ingresso`                                       | Stringa    | Dettagli relativi all'ingresso (es. accessibilità, posizionamento, ecc.).                       |

---

## Miglioramenti al Dataset

1. **Aumento della Completezza**: Tutte le colonne ora hanno una completezza del 100%, garantendo la presenza dei dati necessari.
2. **Unificazione dello Schema**: Sono state introdotte nuove colonne booleane (`Forma_commercio_*_boolean`) per migliorare la chiarezza e ridurre ambiguità.
3. **Rimozione Duplicati**: Gli identificatori univoci sono stati ottimizzati, aumentando l'unicità e la consistenza.
4. **Standardizzazione dei Tipi di Dato**: I tipi di dato sono stati uniformati per riflettere correttamente il contenuto delle colonne.

---

