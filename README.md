# Apple Shortcut für LNURLw Coupons
Dies ist ein kleiner Shortcut für iOS/iPadOS Geräte, mit dem man im Handumdrehen einen LNURL-withdrawal link erstellen kann. Dieser wird dann einmal als QR Code angezeigt und danach in den Zwischenspeicher des Geräts kopiert, von wo aus man den Link einfach über zB Messenger teilen kann.

Dieser Shortcut soll es erleichtern kleine Beträge als Lightning Spende im value4value Bereich an Content Ersteller zu schicken, ohne dass man diese erst um eine Invoice fragen muss. Nicht jeder hat eine funktionierende LN Address ausgewiesen.
Der Empfänger kann somit Spenden über jeden gängigen Messenger empfangen und sich nach Erhalt aussuchen, auf welche Lightning Wallet er die Spende ausgezahlt haben möchte und ob er die Spende überhaupt annehmen möchte.

Der Spendende kann zusätzlich eine Nachricht in der LNURL encodieren, die dem Empfänger beim Einlösen angezeigt wird.

## Voraussetzungen:
- ein Apple Gerät mit iOS/iPadOS Version 12 oder neuer.
- eine öffentlich zugängliche LNbits Instanz mit dem LNURLw Plugin installiert. Zugriff auf Tor .onion Services ist unter iOS leider nicht möglich. 
(am besten eine eigene LNbits Instanz nutzen, alternativ eine öffentliche wie https://legend.lnbits.com/)

## Einrichtung
Methode 1: Ihr folgt dem Link auf eurem iOS/iPadOS Gerät und lasst euch den Shortcut hinzufügen: https://www.icloud.com/shortcuts/2d4b651d7eb34bea9f99f666c814a41f

Methode 2: Ihr ladet einfach die Datei "LNURL_Tips.shortcut" aus diesem Repo herunter und öffnet diese mit der Shortcuts App auf eurem iPhone/iPad.

Beim Importieren werdet ihr nach dem Link zu eurer LNURLw Api gefragt sowie nach dem dazugehörigen X-Api-Key. Diese beiden Werte findet ihr auf LNbits, im LNURLw Reiter. Dort auf API Info klicken und dann unter dem Unterpunkt "Create a withdraw link".

![LNbits Ansicht](/lnurlwdemo.jpeg "LNbits Ansicht auf die API Zugangsdaten im LNURLw Plugin")

## Support
Wenn euch dieser Shortcut geholfen hat, würde ich mich darüber freuen, wenn ihr ihn retweetet. Wollt ihr mir Value4Value ein paar Sats schicken, geht das auch immer per LN Address an systemling32@lightning.by
