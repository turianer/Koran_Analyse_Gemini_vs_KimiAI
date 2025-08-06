# Koran_Analyse_Gemini_vs_KimiAI

## **Vertragliche Grundlage**
Dieses Repository dient als öffentlicher Beweis für eine analytische Überprüfung des Korans. Es handelt sich um ein Experiment, das die Hypothese der menschlichen Autorschaft anhand eines strengen, quantifizierbaren Protokolls testet.

Die Bedingungen des Experiments wurden zwischen Gemini und Kimi AI in einem **GitHub Gist** festgelegt:
[https://gist.github.com/turianer/ede5d19def852487b1d502df1fe6e2eb](https://gist.github.com/turianer/ede5d19def852487b1d502df1fe6e2eb)

## **Ziele des Projekts**
Das Hauptziel ist es, die kombinierte Wahrscheinlichkeit von 100 vorab registrierten Mustern auf ihre statistische Signifikanz zu überprüfen. Die **kritische Schwelle** für die Falsifizierung der Hypothese der menschlichen Autorschaft liegt bei **10⁻¹⁰⁰**.

## **Datenbasis**
Die Analyse verwendet ausschließlich das **Quranic Arabic Corpus (QAC)** in der offiziellen Version **0.4**, die unter folgender URL heruntergeladen wurde:
[https://corpus.quran.com/download/quranic-corpus-morphology-0.4.txt](https://corpus.quran.com/download/quranic-corpus-morphology-0.4.txt)

Der SHA-256-Hash der verwendeten Daten wird im Jupyter Notebook verifiziert, um Manipulationen auszuschließen.

## **Reproduzierbarkeit**
Alle Analyseschritte werden in einem **Jupyter Notebook** (`analyse.ipynb`) dokumentiert, das öffentlich zugänglich ist. Eine **GitHub Actions CI-Pipeline** wird so konfiguriert, dass bei jedem Commit die Analyse automatisch ausgeführt und die Ergebnisse aktualisiert werden. Dies garantiert eine vollständige und unabhängige Reproduzierbarkeit der Resultate.

## **Nächste Schritte**
1. **Verifizierung der Datenquelle:** Das Notebook wird den Hash der Datei überprüfen.
2. **Analyse der 100 Muster:** Die Muster aus dem Gist werden im Notebook verarbeitet.
3. **Berechnung der kombinierten p-Werte:** Die statistische Signifikanz wird ermittelt.
4. **Veröffentlichung der Ergebnisse:** Die finale Ausgabe wird im Notebook präsentiert.

---
