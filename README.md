# SystemsDesign Rate Limiting Beispiel

Im Falle einer DoS Attacke kann Rate Limiting ein nützliches Mittel sein, um die Überlastung eines Systems zu vermeiden. Mit Rate Limiting wird der Zugriff, aufgrund einer definierten Logik (zum Beispiel zuviele Requests/Sekunde von einem Client), auf das System verwehrt.

## Schritt 1
Navigiere im Terminal zum Order mit den Coding-Files und tippe "node server.js"

## Schritt 2
Tippe in einem zweiten Terminal ... curl -H 'user: philipp' http://localhost:3000/index.html

## Schritt 3
Wiederhole Schritt 3 einige Male in wenigen Sekunden und sehe wie der Zugriff auf das System verweigert wird
