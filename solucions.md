# Solucions - Tasca 2: Git, viatjant pel temps

Part 1: He creat el fitxer README.md amb una breu descripció del repositori. Després he fet el primer commit amb el missatge indicat a l'enunciat.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20164027.png)

Part 2: He creat el fitxer 00-installer-config.yaml amb una configuració de xarxa DHCP per a la interfície enps03. Després he guardat els canvis amb un commit de tipus feat.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20164521.png)

Part 3: He utilitzat la comanda git log per consultar l'historial complet del repositori. Aquesta comanda mostra informació com l'autor, la data i el missatge de cada commit.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20164817.png)

Part 4: He utilitzat git log --oneline per veure l'historial de manera resumida. Així puc identificar ràpidament els commits realitzats.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20164931.png)

Part 5: He executat git show HEAD per consultar els canvis exactes que s'han fet en l'últim commit.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20165528.png)

Part 6: He utilitzat l'extensió Git Graph de Visual Studio Code per visualitzar gràficament l'historial dels commits i consultar els canvis realitzats.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20165842.png)

Part 7: He modificat el nom de la interfície enps03 per eth0 per simular un error. Després he executat git status i he comprovat que Git detectava el fitxer com a modificat.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20165959.png)

Part 8: He utilitzat git restore 00-installer-config.yaml per descartar els canvis realitzats i recuperar la versió anterior del fitxer.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20171500.png)

Part 9: He comprovat que el fitxer ha recuperat la configuració original amb la interfície enps03 i DHCP activat. També he verificat que el repositori no tenia modificacions pendents en aquest fitxer.
[Captura](/img/Captura%20de%20pantalla%202026-11-13%20172403.png)