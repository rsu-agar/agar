# RSU-DoH
RSU-DoH ist ein Java-Programm, welches ein Firefox-Profil mit aktiviertem [DNS over HTTPS](https://en.wikipedia.org/wiki/DNS_over_HTTPS) ("DoH") erstellt, um [DNS-Blocking](https://en.wikipedia.org/wiki/DNS_blocking) zu umgehen.

## Download
[RSU-DoH herunterladen](https://github.com/rsu-agar/agar/releases/download/v1.0/RSU-DoH.jar "RSU-DoH herunterladen")

## Anleitung

1. Firefox herunterladen und installieren ([Link](https://www.mozilla.org/de/firefox/new/))
2. Das Programm hetunterladen.
3. Das Programm starten.
   
   Sollte Firefox im Standard-Installationsverzeichnis `C:\Program Files\Mozilla Firefox` nicht gefunden werden, öffnet sich ein Dialog, bei dem Firefox ausgewählt werden muss (`firefox.exe`).
   
   Das Programm legt nun im gleichen Ordner, in dem es ausgeführt wurde, einen neuen Ordner mit dem Namen `RSU-DoH` an.

   In diesem Ordner wird nun ein neuer Ordner mit dem Schema `ff-profile-DoH-[UUID]` angelegt, welcher ein Firefox-Profil mit voreingestelltem DNS over HTTPS (DoH) beinhaltet. Außerdem wird eine .bat Datei angelegt, um Firefox wieder mit diesem Profil zu starten zu können.

   Firefox wird dannach mit dem zuvor erstellten Profil automatisch gestartet.

   Das Programm (RSU-DoH) schließt sich nach einer Sekunde automatisch.


## Spenden
* Bitcoin 1**RSUDoH**WfyxhRDMew5TZffyM3hPgDoUGK
