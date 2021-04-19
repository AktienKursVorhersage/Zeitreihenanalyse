# Zeitreihenanalyse

## Bearbeiter

- Jan Zecevic (jan.zecevic@sap.com)
- Mohammad Ali Alnaser
- Julie Pines (pinesjulie@googlemail.com)

## Idee

Im Rahmen unserer Untergruppe haben wir uns dazu entschieden, den Aktienkurs-Verlauf der VW-Aktie mit Hilfe einer Zeitreihenanalyse (ARIMA-Modell) zu bestimmen. 

## Umsetzung

Bei der Umsetzung haben wir die Daten in zwei verschiedene Häufigkeiten geteilt:

- Tagesdaten
- Monatsdaten

## Ergebnisse

### ARIMA auf den Tagesdaten

#### Metriken
- Mean squared error: 8.765248364767613
- Mean absolut error: 2.0417516365075223
- R2 Score: 0.9720234226385642

#### Graphik

![Vorhersage vs. Tatsächliche Werte](https://github.com/AktienKursVorhersage/Zeitreihenanalyse/blob/main/img/pred_vs_actual_Day.png "Vorhersage vs. Tatsächliche Werte")
![Konfidenzintervall (95%) der Vorhersagen](https://github.com/AktienKursVorhersage/Zeitreihenanalyse/blob/main/img/pred_confint_Day.png "Konfidenzintervall (95%) der Vorhersagen")

### ARIMA auf den Monatsdaten

#### Metrik
- Mean squared error: 120.84754399906895
- Mean absolut error: 8.102724236914167
- R2 Score: 0.5797799623058117

#### Graphik
![Vorhersage vs. Tatsächliche Werte](https://github.com/AktienKursVorhersage/Zeitreihenanalyse/blob/main/img/pred_vs_actual_Month.png "Vorhersage vs. Tatsächliche Werte")
![Konfidenzintervall (95%) der Vorhersagen](https://github.com/AktienKursVorhersage/Zeitreihenanalyse/blob/main/img/pred_confint_Month.png "Konfidenzintervall (95%) der Vorhersagen")
