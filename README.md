# 🏛️ DomusDocs - Sistema di Gestione Documentale Immobiliare

Gestionale documentale completo, robusto e leggero per la catalogazione, l'archiviazione e lo scadenzario dei documenti immobiliari.

Configurato appositamente per la gestione dei 5 immobili:
- 🏡 **Casa Contessa**
- 🏠 **Casa Paese**
- 🌊 **Casa Marina**
- 🏢 **Casa Quattromiglia**
- 🏘️ **Casa Villaggio Europa**

Zero dipendenze esterne a scadenza, zero cookie o tracciamento: funziona interamente via browser con **IndexedDB** per lo storage locale persistente di metadati e scansioni (PDF, PNG, JPG), con supporto a backup/ripristino completo in JSON.

---

## 📁 Le 6 Categorie Documentali per ciascun Immobile

1. **Catasto & Proprietà**: Atto di acquisto/rogito, visura catastale storica, planimetrie quotate, estratti di mappa.
2. **Attestati & Conformità (Impianti)**: Certificato APE (decennale), conformità impianti (elettrico, gas, riscaldamento), agibilità.
3. **Contratti & Locazioni**: Contratti di locazione stipulati, ricevuta telematica RLI Agenzia delle Entrate, adesione cedolare secca, verbali di consegna / inventari fotografici.
4. **Fisco & Tasse**: Ricevute F24 versamento IMU, avvisi e ricevute TARI, dichiarazioni IMU, imposta di registro.
5. **Condominio**: Regolamento di condominio, tabelle millesimali, convocazioni/verbali assemblea, riparto consuntivo/preventivo spese.
6. **Manutenzioni & Spese**: Libretto di impianto termico / bollino blu caldaia, fatture ristrutturazioni/interventi, garanzie.

---

## 🛠️ Come Eseguire o Pubblicare su GitHub

### Opzione 1: Uso Locale Immediato
Scarica ed estrai l'archivio ZIP, poi fai doppio clic su `index.html`. Funziona subito in qualsiasi browser (Chrome, Edge, Firefox, Safari).

### Opzione 2: Pubblicazione su GitHub Pages
1. Crea un repository su GitHub (es. `domusdocs`).
2. Clona ed esegui il push dei file:
   ```bash
   git init
   git add .
   git commit -m "feat: setup domusdocs with custom properties"
   git branch -M main
   git remote origin https://github.com/TUO-USERNAME/NOME-REPO.git
   git push -u origin main
   ```
3. Vai nelle impostazioni del repository su GitHub (`Settings` -> `Pages`).
4. Sotto **Branch**, seleziona `main` e cartella `/ (root)`, poi clicca **Save**.
5. L'app sarà subito disponibile online all'indirizzo `https://TUO-USERNAME.github.io/NOME-REPO/`.
