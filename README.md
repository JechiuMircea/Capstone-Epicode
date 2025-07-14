# NBA Analysis Project

## 📊 Descrizione del Progetto

Questo progetto è un'analisi parziale dei dati NBA che include:
- Analisi delle partite e statistiche
- Visualizzazioni geografiche delle squadre
- Dashboard interattive
- Analisi degli MVP delle Finals

## 🗂️ Struttura del Progetto

```
Capstone/
├── BackupTabelleDataset/          # Backup dei dataset originali
├── DataPuliti/                    # Dataset puliti e pronti per l'analisi
│   ├── Games.csv                  # Dati delle partite
│   ├── LeagueSchedule24_25.csv    # Calendario stagione 2024-25
│   ├── NBA_CityCoordinates_Found.csv  # Coordinate geografiche delle città
│   └── ...                        # Altri dataset puliti
├── DataSetOriginale.csv/          # Dataset originali non modificati
├── FilePython/                    # Script Python per l'elaborazione dati
│   ├── converti_coordinate_csv.py # Conversione coordinate
│   ├── aggiorna_dataset_con_immagini_nba.py
│   └── ...                        # Altri script di elaborazione
├── Grafici/                       # Output delle visualizzazioni
│   ├── nba_analysis.png
│   ├── nba_champions_dashboard.png
│   └── ...                        # Altri grafici e dashboard
├── Immagini_MVP_Finals/           # Immagini degli MVP
├── Nba_env/                       # Ambiente virtuale Python
├── TextFile/                      # Documentazione e note
└── requirements.txt               # Dipendenze Python
```

## 🚀 Funzionalità Principali

### 📈 Analisi Dati
- **Analisi delle partite**: Statistiche dettagliate delle partite NBA
- **Analisi MVP Finals**: Studio degli MVP delle Finals NBA
- **Dashboard interattive**: Visualizzazioni dinamiche dei dati

### 🛠️ Strumenti di Elaborazione
- **Script Python**: Automatizzazione della pulizia e elaborazione dati
- **Aggiornamento dataset**: Script per mantenere i dati aggiornati

### 📊 Visualizzazioni
- **Grafici statici**: PNG per presentazioni

## 🛠️ Installazione

### Prerequisiti
- Python 3.8+
- Power BI Desktop (per le dashboard)
- Git (per il controllo versione)


## 📖 Utilizzo

### Elaborazione Dati
```bash

# Aggiornamento dataset
python FilePython/aggiorna_dataset_con_immagini_nba.py
```

### Visualizzazioni
1. Apri Power BI Desktop
2. Importa i file da `DataPuliti/`
3. Crea le visualizzazioni desiderate
4. Esporta i risultati in `Grafici/`

## 📁 Dataset Principali

### Games.csv
- Dati delle partite NBA
- Statistiche dettagliate


## 🔧 Script Utili


### aggiorna_dataset_con_immagini_nba.py
Aggiorna i dataset con nuove informazioni e immagini.

## 📊 Output

### Grafici Generati
- `nba_analysis.png`: Analisi generale NBA
- `nba_champions_dashboard.png`: Dashboard dei campioni
- `nba_finals_mvp_analysis.png`: Analisi MVP Finals

### Dashboard HTML
- Visualizzazioni interattive
- Grafici dinamici
- Filtri personalizzabili

## 🤝 Contributi

Per contribuire al progetto:
1. Fai un fork del repository
2. Crea un branch per le tue modifiche
3. Committa le modifiche
4. Crea una Pull Request

## 📝 Note Tecniche


### Codifica File
- **Encoding**: UTF-8
- **Separatore**: Virgola
- **Formato**: CSV standard



## 📞 Supporto

Per problemi o domande:
- Controlla la documentazione in `TextFile/`
- Verifica i log degli script Python
- Controlla la compatibilità delle versioni

## 📄 Licenza

Questo progetto è per uso educativo e di ricerca.

---

**Ultimo aggiornamento**: Giugno 2025
**Versione**: 1.0 