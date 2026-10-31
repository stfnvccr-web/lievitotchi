# Lievitotchi 🍞👾

Un'applicazione in stile **Tamagotchi** rétro per la cura, il monitoraggio biologico e la pianificazione dei rinfreschi del proprio lievito madre (sia **Li.Co.Li** al 100% di idratazione che **Pasta Madre Solida** al 50%).

## 🔬 Fondamenti Scientifici
- **Cinetica di Fermentazione:** Simulazione dell'attività microbiologica di lieviti (*Saccharomyces cerevisiae*, *Candida humilis*) e batteri lattici eterofermentanti/omofermentanti (*Fructilactobacillus sanfranciscensis*).
- **Controllo Termico:** Modalità Frigorifero (+4°C) con abbattimento metabolico stimato dell'85-88% in base al coefficiente $Q_{10}$.
- **Idratazione Differenziata:** Calcolatore automatico stechiometrico di farina e acqua per coltura solida (50%) o liquida (100%).
- **Calcolo Acidità & Picco:** Tracciamento del rapporto acidi volatili (acido acetico) e non volatili (acido lattico) per prevenire la degradazione della maglia glutinica prima dell'impasto.

## 🎯 Programmi di Impegno Cucina
1. **Zen (Minimo Sforzo):** Mantenimento sereno in frigorifero con rinfreschi distanziati (7-10 giorni) ad alto rapporto nutrizionale (1:2 / 1:3).
2. **Weekend Chef:** Ottimizzato per pizza o pane al sabato/domenica, con piano orario di risveglio il venerdì e picco a mezzogiorno del sabato.
3. **Panettiere Pro:** Cicli ravvicinati e lievito tenuto a temperatura controllata per infornate multiple.

## 🚀 Come avviare
Apri semplicemente il file `index.html` con qualsiasi browser web moderno, oppure servilo tramite un semplice server HTTP locale:
```powershell
python -m http.server 8080
```
e naviga su `http://localhost:8080`.
