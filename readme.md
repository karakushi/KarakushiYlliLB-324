# LB 324

## Aufgabe 2, Wie installiere ich "pre-commit"?
Um automatisierte Code-Tests und Code-Formattierung bei meinem Projekt anzuwenden muss ich pre-commit installieren, aber wie geht das?

#### Schritt 1
Du sollst pre-commit installieren:
```pip install pre-commit```

#### Schritt 2
Jedoch muss deine Repository up to date sein, also:
```pre-commit install```

#### Schritt 3
Wenn nun etwas im Code bearbeitet wird, kann man entweder Push (wird auf Server geladen) oder Commit (wird lokal aktualisiert) machen, ohne dass man noch testen muss. Es passiert nun alles automatisch⚙️.

## Aufgabe 4, Wie übertrage ich das Passwort aus der .env Datei auf Azure?
Link zur Website: karakushiyllilb-324.azurewebsites.net

#### Schritt 1
Ich gehe auf die Seite portal.azure und melde mich mit meiner BBB-EMail an. Danach muss ich ein Deployment machen.

#### Schritt 2
Danach gehe ich unter Configurations/New application setting , wo ich das Password eingebe
![image](https://github.com/karakushi/KarakushiYlliLB-324/assets/118426881/73161935-3cc8-45af-b0f9-f3e4e7551971)

#### Schritt 3
Danach gebe ich das gleiche ein wie bei meiner .env Datei. --> Name: PASSWORD, Value: "verysecretpassword😮😮😮" und klicke die Box an.
