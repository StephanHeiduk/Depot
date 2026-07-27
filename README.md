# Depot — Strategie und Auswertung

Dieses Repository enthält ein selbst gebautes Dashboard, mit dem ich mein
Wertpapierdepot verfolge. Es liest die Abrechnungen meines Brokers aus, rechnet
daraus Bestand, Kosten und Rendite und holt sich die Kurse live nach.

**→ [Zum Dashboard](https://stephanheiduk.github.io/Depot/)**

---

## Die Strategie in Kürze

**Ein Verfahren, keine Meinungen.** Was gekauft wird, entscheidet nicht mein
Bauchgefühl zu einem einzelnen Unternehmen, sondern eine Recherche nach festen,
vorab definierten Parametern. Was dabei herauskommt, wird gekauft — auch dann,
wenn mir die Aktie auf den ersten Blick nicht gefällt. Und was nicht
herauskommt, wird nicht gekauft, egal wie überzeugend die Geschichte klingt.

**Die Branchenmischung ist ein Ergebnis, keine Vorgabe.** Ich lege vorher nicht
fest, wie viel in welchen Sektor soll. Dass in einem Monat Hardware-Werte aus
dem Rechenzentrums-Umfeld herauskommen und im nächsten Konsumgüter, Handel und
Reise, sagt etwas über die Marktlage aus — nicht über eine Absicht von mir.

**Fester Termin.** Gekauft wird in einem monatlichen Rhythmus zum Monatsanfang.
Kein Warten auf den günstigen Moment: der Termin steht fest, die Auswahl wird
davor erarbeitet.

**Feste Tranchen.** Jede Position wird in einer von zwei Größen aufgebaut, die
größere ist die doppelte der kleineren. Das hält die Gewichtung im Griff und
verhindert, dass Überzeugung heimlich in die Positionsgröße rutscht.

**Feste Haltedauer statt Ausstiegsgefühl.** Jede Position hat eine Lebensdauer
von höchstens drei Monaten und wird danach automatisch verkauft. Das ist der
Kern: Es gibt keinen Moment, in dem ich mir überlegen muss, ob ich noch an eine
Aktie glaube. Der Ausstieg ist beim Einstieg schon festgelegt. Dadurch kann eine
Position weder zum Liebling noch zum Sitzenbleiber werden, und aus einem
Verlierer wird keine Langzeitbeziehung.

**Einzelwerte statt Fonds.** Gekauft werden einzelne Aktien. Das ist die
bewusste Entscheidung, für das Verfahren geradezustehen — mit dem Dashboard als
ehrlicher Rückmeldung, ob es etwas taugt.

**Kosten werden mitgezählt.** Jeder Kauf und jeder Verkauf kostet eine feste
Pauschale, unabhängig vom Volumen — bei einer Haltedauer von drei Monaten fällt
sie also zweimal je Position an. Bei kurzen Haltedauern ist das kein Rundungsfehler,
sondern eine Hürde, die die Strategie erst einmal überspringen muss. Das
Dashboard weist die Kostenquote deshalb offen aus. Gebühren und Quellensteuern
stecken in allen Renditezahlen; nichts wird schöngerechnet.

---

## Wie man das Dashboard liest

| Kennzahl | Bedeutung |
|---|---|
| **Gesamtergebnis** | Depotwert plus erhaltene Dividenden minus allem, was ich eingezahlt habe. Die Zahl, die zählt. |
| **TWR** | Zeitgewichtete Rendite: misst die Qualität des Verfahrens. Wann wie viel eingezahlt wurde, verzerrt sie nicht. |
| **IRR** | Geldgewichtete Rendite: misst, was das tatsächlich eingesetzte Geld verdient hat. |
| **p. a.** | Auf ein Jahr hochgerechnet. Bei kurzer Laufzeit eine Schätzung, keine Prognose. |

Dass TWR und IRR auseinanderlaufen, ist kein Fehler, sondern der interessanteste
Teil: ein gutes Verfahren nützt wenig, wenn das meiste Geld erst spät und auf
hohem Niveau dazukommt. Genau das macht der Vergleich beider Zahlen sichtbar.

Weil jede Position nach spätestens drei Monaten geschlossen wird, ist die
einzelne Aktie ohnehin nicht die interessante Einheit. Aussagekräftig wird das
Ganze erst über viele abgeschlossene Durchläufe hinweg — ein einzelner guter
oder schlechter Monat sagt über das Verfahren fast nichts.

Weil die Haltedauer der Kern der Sache ist, führt der Reiter **Positionen**
zuerst die **Fälligkeiten** auf: jede offene Tranche mit Kaufdatum, bisheriger
Haltedauer, Verkaufstermin und Restlaufzeit. Was in den nächsten sieben Tagen
ausläuft, ist hervorgehoben. So ist jederzeit sichtbar, wie viel Kapital
demnächst wieder frei wird.

Die weiteren Reiter zeigen die offenen Positionen mit Einstand und aktuellem
Wert, den Verlauf nach Tag, Woche, Monat und Jahr, alle Buchungen sowie eine
automatische Prüfung der Belege gegeneinander.

---

## Was hier bewusst offen bleibt

Zu sehen ist das **Ergebnis**, nicht der **Weg dorthin**. Nicht Teil dieser
Darstellung sind:

- die Parameter, nach denen die Recherche filtert, und ihre Schwellenwerte
- die Datenquellen und Auswertungen dahinter
- das Universum, aus dem gesucht wird
- die Kandidaten, die es in einem Monat knapp nicht geschafft haben
- der Anteil dieses Depots an meinen Ersparnissen insgesamt

Das Dashboard ist mein Kontrollinstrument, keine Anleitung zum Nachmachen.

---

## Hinweis

Keine Anlageberatung und keine Empfehlung. Ich zeige, was ich selbst mache und
wie es läuft — einschließlich der Phasen, in denen es nicht läuft. Ein Verfahren
mit kurzer Haltedauer erzeugt zwangsläufig auch Verlustmonate; wer nur auf die
guten schaut, versteht es nicht. Wertpapiere können an Wert verlieren,
vergangene Entwicklungen sagen nichts über künftige. Wer daraus eigene
Entscheidungen ableitet, trifft sie auf eigene Rechnung.

Die Kurse stammen von der jeweiligen Heimatbörse und werden mit dem
EZB-Referenzkurs in Euro umgerechnet. Kleine Abweichungen zur Anzeige des
Brokers sind dadurch normal.
