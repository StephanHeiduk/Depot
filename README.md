[README.md](https://github.com/user-attachments/files/30426057/README.md)
# Depot — Strategie und Auswertung

Dieses Repository enthält ein selbst gebautes Dashboard, mit dem ich mein
Wertpapierdepot verfolge. Es liest die Abrechnungen meines Brokers aus, rechnet
daraus Bestand, Kosten und Rendite und holt sich die Kurse live nach.

**→ [Zum Dashboard](https://stephanheiduk.github.io/Depot/)**

---

## Die Strategie in Kürze

**Regelmäßig statt punktuell.** Gekauft wird in einem festen monatlichen Rhythmus,
jeweils zum Monatsanfang. Kein Markttiming, kein Warten auf den richtigen Moment —
der Termin steht fest, die Auswahl wird davor getroffen.

**Feste Tranchen.** Jede Position wird in einer von zwei Größen aufgebaut, wobei
die größere die doppelte der kleineren ist. Das hält die Gewichtung im Depot
kontrollierbar und macht Positionen untereinander vergleichbar, ohne dass ich
über jede Ordergröße neu nachdenken muss.

**Einzelwerte statt Fonds.** Gekauft werden einzelne Aktien, keine ETFs. Das ist
die bewusste Entscheidung, für die Auswahl selbst geradezustehen — mit dem
Dashboard als ehrlicher Rückmeldung, ob sie etwas taugt.

**Zwei Bausteine.** Der erste Teil des Depots liegt in einem konkreten
Technologie-Thema, dessen Nachfrage aus dem Ausbau von Rechenzentren kommt.
Diese Werte schwanken stark und werden entsprechend klein gehalten. Der zweite
Teil besteht aus etablierten, wenig zyklischen Unternehmen mit stabilem Geschäft
und bekannten Marken. Der zweite Teil ist der Gegengewichts-Baustein: er soll
ruhig bleiben, wenn der erste nicht ruhig ist.

**Kaufen und halten.** Bisher wurde nichts verkauft. Positionen werden aufgebaut
und gehalten; ein Verkauf wäre eine eigene Entscheidung mit eigener Begründung,
keine Reaktion auf einen schlechten Monat.

**Nicht jede geprüfte Order wird ausgeführt.** Zu einzelnen Werten liegen
Kostenvorschauen vor, ohne dass es zu einem Kauf kam. Eine Idee bis zur
Ordermaske zu verfolgen und sie dann liegen zu lassen, gehört dazu.

**Kosten werden mitgezählt.** Jede Order kostet eine feste Pauschale, unabhängig
vom Volumen. Das Dashboard weist die Kostenquote deshalb offen aus: sie ist bei
der doppelten Tranche halb so hoch wie bei der einfachen. Gebühren und
Quellensteuern sind in allen Renditezahlen enthalten, nichts wird schöngerechnet.

---

## Wie man das Dashboard liest

| Kennzahl | Bedeutung |
|---|---|
| **Gesamtergebnis** | Depotwert plus erhaltene Dividenden minus allem, was ich eingezahlt habe. Die Zahl, die zählt. |
| **TWR** | Zeitgewichtete Rendite: misst die Qualität der Auswahl. Wann wie viel eingezahlt wurde, verzerrt sie nicht. |
| **IRR** | Geldgewichtete Rendite: misst, was das tatsächlich eingesetzte Geld verdient hat. |
| **p. a.** | Auf ein Jahr hochgerechnet. Bei kurzer Laufzeit eine Schätzung, keine Prognose. |

Dass TWR und IRR auseinanderlaufen, ist kein Fehler, sondern der interessanteste
Teil: eine gute Auswahl nützt wenig, wenn das meiste Geld erst spät und auf hohem
Niveau dazukommt. Genau das macht der Vergleich beider Zahlen sichtbar.

Die Reiter darüber hinaus zeigen die einzelnen Positionen mit Einstand und
aktuellem Wert, den Verlauf nach Tag, Woche, Monat und Jahr, alle Buchungen
sowie eine automatische Prüfung der Belege gegeneinander.

---

## Was hier bewusst offen bleibt

Zu sehen ist das **Ergebnis**, nicht der **Weg dorthin**. Nicht Teil dieser
Darstellung sind:

- die Kriterien, nach denen ein Unternehmen in die Auswahl kommt
- die Quellen und Auswertungen, auf denen die Entscheidungen beruhen
- die Kandidaten, die beobachtet, aber (noch) nicht gekauft werden
- die Regeln, wann eine Position vergrößert oder aufgelöst wird
- der Anteil dieses Depots an meinen Ersparnissen insgesamt

Das Dashboard ist mein Kontrollinstrument, keine Anleitung zum Nachmachen.

---

## Hinweis

Keine Anlageberatung und keine Empfehlung. Ich zeige, was ich selbst mache und
wie es läuft — einschließlich der Phasen, in denen es nicht läuft. Wertpapiere
können an Wert verlieren, vergangene Entwicklungen sagen nichts über künftige.
Wer daraus eigene Entscheidungen ableitet, trifft sie auf eigene Rechnung.

Die Kurse stammen von der jeweiligen Heimatbörse und werden mit dem
EZB-Referenzkurs in Euro umgerechnet. Kleine Abweichungen zur Anzeige des Brokers
sind dadurch normal.
