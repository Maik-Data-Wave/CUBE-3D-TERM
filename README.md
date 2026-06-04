# CUBE-3D-TERM
-- Data over Sound -- 
- ALPHA Version 15 (Test Betrieb in HTML)


  
Das Programm ist im Aufbau! Es ist ein Kommunikationsprogramm für CB Funk. 
Hier werden 3 Töne zur gleichen Zeit gesendet auf X/Y/Z Achsen und genauso dekodiert, daher CUBE 3D. Das Programm ist so ausgelegt, das die Squelch am Funkgerät offen sein muss/kann! 

Es arbeitet NICHT wie Packet Radio! Es ist KEIN AX25! 

Das ist ein einfaches Messanger Programm. Jeder muss sich einen Namen geben. 6 Stellen(wie bei Packet Radio) insgesammt XXXYYYY, dies ist dann dein Mycall. Als Ziel gibt man die Gegenstation im Target an. Zusätzlich kann man bis zu 3 VIA's benutzen (Sprungstationen).
Ein ChatCall kann man auch angeben. Wenn das gemacht worden ist, bekommt jeder eine Nachricht, der den gleichen ChatCall(GruppenChat) hat! 

Die Daten werden dann über Sound ausgegeben und über Mic eingelesen. Man kann entweder, manuell das Mike übern Lautsprecher halten oder eine der PTT-Arten (VOX/RS232) wählen. Um Daten zu emfangen, reicht es, das Mikrofon dicht am Lautsprecher zu legen (Achtung!Nebengeräusche zerstören die Übertragung) oder man schließt es am Lautsprecherausgang (Achtung! Hohe Spannung kann den PC Zerstören) des Funkgerätes an! Die Lautstärke muss einreguliert werden am Laut/Leisesteller des Funkgerätes. Weitere Einstellungen, wie Mic und Lautsprecher am PC, werden unter den PC Einstellungen der Soundkarte für Optimierungen vorgenommen. Jeder handelt auf eigenes Risiko! Ich übernehme keine Haftung für Hard und Software! 

Im Programm ist integriert:
-CMD ON/OFF (Nur ein Test)
-Monitor ON/OFF
-BAKE ON/OFF
-SETUP
-PTT (ON/OFF, RS232/TON)
-MAILBOX BBS(MINI)
-MHEARD
-CALLBOOK
-INPOERT/EXPORT der Einstellungen

Auswahl der Aussendung (Links neben der Payload):
-MSG (Einfachen Text an Call oder Chat senden)
-BELL (EIN Klingeln auslösen an der Gegenstation)
-Ping (Ein Anpingen an der Gegenstation mit Autoantwort)
-CMD (Ein Fernsteuerungsanfrage Auslösen [NUR TEST])

Befehle BBS: ?L (Liste der Mails zu mir senden), ?R[ID] (Zeige Eindrag mit der Nummer), ?S AN BETREFF TEXT (Eine Nachricht hinterlegen auf der BBS der Gegenstation),?D[ID] Nachricht löschen auf der Gegenstation

Befehle CMD(TEST): ?VERSION (Version der Gegenstation anzeigen), ?STATUS (Stationsname, Systemzeit der Gegenstation), ?PING (Die Gegenstation sendet ein PONG), ?HILFE (Die Gegenstation listet die Befehle)

Wichtig! Es ist erst eine ALPHA Version und das bedeutet, es können eventuell noch Fehler im Betrieb Auftauchen ;-)
Viel Spass beim Testen :-) Über ein Feedback würde ich mich freuen :-)

#HTML #JAVASCRIPT #C++ #WASM #CB #FUNK #SQUELCH #GATEWAY #DIGIPEATER #MESSAGE #CALL #DSP #DATA-OVER-SOUND #PACKET-RADIO #MESSAGE #CALL #NACHRICHTEN #BELL #ALARM 

<img width="1920" height="907" alt="Bildschirmfoto_2026-06-03_15-24-26" src="https://github.com/user-attachments/assets/bf5323b9-585c-41be-b53f-b56737db7bf2" />
<img width="1920" height="910" alt="Bildschirmfoto_2026-06-03_15-23-55" src="https://github.com/user-attachments/assets/f460e0e9-a618-4608-ae47-d220e8fcb7fe" />
<img width="1920" height="901" alt="Bildschirmfoto_2026-06-03_15-23-38" src="https://github.com/user-attachments/assets/173d8921-f7e3-4176-a081-559865bd16ba" />
<img width="1920" height="905" alt="Bildschirmfoto_2026-06-03_15-23-06" src="https://github.com/user-attachments/assets/70b3c8d9-eeca-4464-be73-ae0dbad8c7e7" />
<img width="1918" height="907" alt="Bildschirmfoto_2026-06-03_15-22-40" src="https://github.com/user-attachments/assets/d1f6695c-5390-48b1-b9bc-9334ea2e2e1f" />
<img width="1920" height="912" alt="Bildschirmfoto_2026-06-03_15-22-23" src="https://github.com/user-attachments/assets/a4766abc-cc3a-4b43-bc02-81c60c9135db" />
<img width="1919" height="907" alt="Bildschirmfoto_2026-06-03_15-22-07" src="https://github.com/user-attachments/assets/9bc0405d-9f63-4824-8951-234d1c958386" />
<img width="1919" height="907" alt="Bildschirmfoto_2026-06-03_15-21-49" src="https://github.com/user-attachments/assets/b4ba9804-f407-4fa6-bc70-89044751cccd" />


