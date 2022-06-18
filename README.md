# Paint Bots DE (Development Environment)

## QuickStart
Dies ist ein Gradle-Projekt, dass einen einfachen Start zur Programmierung deines Bots für den Programmierwettbewerb bietet.
Es ist zur Verwendung in IntelliJ entworfen, da es über Gradle funktioniert kann es aber in einer beliebigen IDE importiert werden.

## IntelliJ Guide
Um das Projekt in IntelliJ zu importieren, gehe in IJ auf File > New > Project from Version Control </br>, 
trage bei URL den Link zu diesem Repo ein (https://github.com/CorneliusZenker/PaintBotDE) und bestätige mit Klick auf [Clone].
Anschliessend öffnest du den Reiter Gradle am rechten Rand und führst die Task runGame (unter PaintBotDE/Tasks/other) aus.
Dies fügt die Configuration hinzu, die du wie gewohnt nutzen kannst, um dein Programm zu starten und zu debuggen.

## FAQ
Die meisten Antworten auf deine Fragen wirst du bereits im Original Repo von Thomas Wilde finden: https://github.com/Thomas-Wilde/PaintBots/blob/main/README.md

#### Was mache ich, wenn es im Repo eine neue Version gibt?
Für diesen Fall musst du die Änderungen vom Remote Branch origin/master in deinen lokalen Branch mergen. 
Unter IJ kannst du einfach auf VCS > Update Project  klicken (Ist nur ein angenehmer Shortcut).
Deine Bots im Package Bots bleiben unverändert, <b>solange sie nicht RandomBot.java heißen</b>.

Daher solltest du Sie spätestens umbenennen, bevor du einen solchen Merge/ Update durchführst. 
Am besten ist es jedoch das Template einfach zu kopieren, wenn du mit programmieren beginnst und es dabei schon umzubenennen.

Es kann zudem passieren, dass ein Merge die paintBots.jar updatet. Sollte danach deine Code-Inspection nicht mehr funktionieren, 
lässt sich das leicht mit einem Neustart der IDE beheben.
Sollte auch das Kompilieren fehlschlagen, ist dies warscheinlich ein Bug. Schreib mich in diesem Fall gerne an.

#### Gibt es auch Anleitungen für andere IDEs?:
Nein, gibt es nicht. Wenn du dich darüber beschwehren willst, 
hättest du vor 3 Wochen anfangen sollen und bei Problemen Leute im Fin-Emporium ansprechen müssen. ¯\\\_(ツ)\_/¯

#### Ich habe einen Bug gefunden:
Schreibe mir gerne auf Discord oder im Aud Channel vom Fin-Emporium

