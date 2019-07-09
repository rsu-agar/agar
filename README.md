# RSU-DoH
RSU-DoH ist ein Java-Programm, welches ein Firefox-Profil mit aktiviertem [DNS over HTTPS](https://en.wikipedia.org/wiki/DNS_over_HTTPS) ("DoH") erstellt, um [DNS-Blocking](https://en.wikipedia.org/wiki/DNS_blocking) zu umgehen.

## Download
[**RSU-DoH herunterladen**](https://github.com/rsu-agar/agar/releases/download/v1.0/RSU-DoH.jar "RSU-DoH herunterladen")


## Anleitung

1. Das Programm hetunterladen.

2. Das Programm starten.

3. Sollte Firefox im Standard-Installationsverzeichnis `C:\Program Files\Mozilla Firefox` nicht gefunden werden, öffnet sich ein Dialog, bei dem Firefox ausgewählt werden muss (`firefox.exe`).
   
4. Das Programm legt nun im gleichen Ordner, in dem es ausgeführt wurde, einen neuen Ordner mit dem Namen `RSU-DoH` an.

5. In diesem Ordner wird nun ein neuer Ordner mit dem Schema `ff-profile-DoH-[UUID]` angelegt, welcher ein Firefox-Profil mit voreingestelltem DNS over HTTPS (DoH) beinhaltet. Außerdem wird eine .bat Datei angelegt, um Firefox wieder mit diesem Profil zu starten zu können.

6. Firefox wird dannach mit dem zuvor erstellten Profil automatisch gestartet.

7. Das Programm (RSU-DoH) schließt sich nach einer Sekunde automatisch.
