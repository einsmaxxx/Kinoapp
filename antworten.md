\# Antworten – Git-Generalprobe



\## Teil A – Orientierung



\*\*A1:\*\* Ich bin auf dem Branch main. Weitere Branches waren feature/snacks und feature/neuer-titel.



\*\*A2:\*\* Untracked bedeutet, dass Git diese Dateien noch nicht kennt und sie noch nicht verfolgt.



\*\*A3:\*\* Im Ordner .git sind die Git-Daten, Commits und Branches gespeichert. Wenn man ihn löscht, geht die Git-Historie verloren.



\## Teil B – Fast-Forward-Merge



\*\*B1:\*\* Im Log sieht man, dass main einfach weitergesetzt wurde. Es wurde kein neuer Merge-Commit erstellt.



\*\*B2:\*\* Weil main noch keine eigenen Änderungen hatte und direkt auf feature/snacks folgen konnte.



\## Teil C – Fehler finden



\*\*C1:\*\* Der Fehler lag in der Altersabfrage. Personen über 14 bekamen fälschlicherweise den Kinderpreis.



\*\*C2:\*\* Nach git add ist die Änderung vorgemerkt. Deshalb zeigt git diff nichts mehr, aber git diff --staged zeigt die Änderung.



\## Teil D – Commit zurücknehmen



\*\*D1:\*\* Der alte Commit bleibt in der Historie. Es kommt ein neuer Revert-Commit dazu.



\*\*D2:\*\* Damit bleibt die Historie erhalten und das Team kann weiterhin alle Änderungen nachvollziehen.



\## Teil E – .gitignore



\*\*E1:\*\* > überschreibt den Inhalt einer Datei. >> fügt neuen Inhalt hinzu.



\*\*E2:\*\* Vorher wurden die nicht versionierten Dateien angezeigt. Nach der .gitignore werden test/ und Logdateien ignoriert.



\## Teil F – Merge-Konflikt



\*\*F1:\*\* Weil beide Branches unterschiedliche Änderungen hatten und Git keinen einfachen Fast-Forward machen konnte.



\*\*F2:\*\* HEAD steht für den aktuellen Branch. feature/neuer-titel ist der andere Branch.



\*\*F3:\*\* Weil beide Branches dieselbe Zeile unterschiedlich geändert haben.



\## Teil G – GitHub



\*\*G1:\*\* Weil git status noch den alten Stand von origin/main vergleicht. Die neue Änderung war lokal noch nicht bekannt.



\*\*G2:\*\* git fetch lädt neue Änderungen herunter. git pull lädt sie herunter und übernimmt sie direkt in den aktuellen Branch.



\*\*G3:\*\* -u merkt sich den Remote-Branch. Beim nächsten Push muss man ihn nicht erneut angeben.



\*\*G4:\*\* Weil die Datei zuerst auf GitHub zusammengeführt wurde. Erst mit git pull wurde sie auch lokal übernommen.

