# AI-Projekt von Hendrik Stolzke DBE1
Matrikelnummer: 821534 
Thema: eBay Preisvorhersage mit Machine Learning

Dieses Projekt beschäftigt sich mit der Entwicklung eines Machine-Learning-basierten Regressionsmodells zur Vorhersage von Endpreisen bei eBay-Auktionen. 
Ziel ist es, aus historischen Auktionsdaten Muster zu lernen und daraus präzise Preisprognosen sowie verschiedene Anwendungsszenarien für die Plattform abzuleiten.

---

## Projektziel

Das Ziel des Projekts ist die Entwicklung eines Modells, das den finalen Auktionspreis möglichst genau vorhersagen kann. 

---

## Projektstruktur

Das Projekt ist wie folgt aufgebaut:

- Drei CSV-Dateien mit Daten zu verschiedenen Auktionslängen  
- Ein Jupyter Notebook mit der vollständigen Implementierung des Codes  
- Die schriftliche Hausarbeit zur Projektbeschreibung und Analyse  
- Das trainierte KI-Modell als `.pkl`-Datei  

---

## Das KI-Modell

Es wurde ein **Random-Forest-Regressor** verwendet, der auf strukturierten Auktionsdaten trainiert wurde. 
Das Modell lernt Zusammenhänge zwischen verschiedenen Features.

### Evaluation

- Testdatensatz: 20 % der Gesamtdaten  
- Metrik: Mean Absolute Error (MAE)  
- Ergebnis: **MAE ≈ 10,97 €**

Die Vorhersagen weichen damit im Durchschnitt um etwa 11 Euro vom tatsächlichen Endpreis ab.

---

## 📈 Anwendungsfälle

### Dynamische Angebotsoptimierung
Verkäufer erhalten Empfehlungen zur Optimierung ihrer Listings, z. B. zur Auktionsdauer oder zum Startzeitpunkt.

### Betrugserkennung
Signifikante Abweichungen zwischen vorhergesagtem und tatsächlichem Preis können auf mögliche Manipulationen hinweisen.

### Marktanalyse
Visualisierung von Preisentwicklungen, saisonalen Trends und Vergleich mit dem Marktdurchschnitt.

### Personalisierte Empfehlungen
Nutzer können Benachrichtigungen über besonders günstige oder relevante Auktionen erhalten.

---

## Der Wirtschaftliche Nutzen

Der Einsatz des Modells kann für eBay folgende Vorteile bringen:

- Steigerung der Plattformeffizienz  
- Erhöhung der Nutzerbindung  
- Verbesserung der Transaktionsraten  
- Reduktion von Support-Anfragen  
- Aufbau datengetriebener Wettbewerbsvorteile  

---

## Technologien

- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib / seaborn (für Analyse und Visualisierung)

---

## Fazit

Das Projekt zeigt, wie Machine Learning genutzt werden kann, um Preisbildungsmechanismen auf Auktionsplattformen besser zu verstehen und aktiv zu optimieren. 
Neben der reinen Preisvorhersage ergeben sich zahlreiche strategische Einsatzmöglichkeiten für Plattformbetreiber wie eBay.
