Hallo und willkommen zum Methoden-Workshop _„How to build an artificial Coder? Einführung in die automatisierte Inhaltsanalyse mit Machine Learning“_ des Nachwuchsnetzwerks politische Kommunikation [NapoKo](http://napoko.de/)! Den Call für den Workshop findet ihr [hier](http://napoko.de/workshop-artificial-coder/). 

Bei Fragen zum Inhalt schreibt einfach eine Mail an die Dozentin [Anke Stoll](mailto:anke.stoll@hhu.de). 

Für organisatorische Fragen meldet euch gerne bei [Katharina Esau](mailto:katharina.esau@hhu.de) (Sprecherin NapoKo).

Wir wünschen euch viel Spaß :two_hearts:

### Hier kannst du das Material herunterladen 

Klicke [hier](https://github.com/ankekat1000/Workshop-ML-Automatisierte-Inhaltsanalyse/archive/main.zip), um den Workshop-Ordner als **.zip-Datei** von [GitHub](https://github.com/ankekat1000/Workshop-ML-Automatisierte-Inhaltsanalyse) herunterzuladen. Im Workshop-Ordner findest du alle **Skripte, Folien und Datensätze**, die wir im Workshop benutzen. Aktuell ist ein Datensatz zum Ausprobieren und die Datei `requirements.ipynb` (s. unten) mit den benötigten Packages hochgeladen. Folien und die Skripte, die wir im Workshop erstellen, werden nach dem Workshop ebenfalls hier verfügbar sein. 

### Workshop-Agenda

Der Workshop findet am Donnerstag, den 11.02.2020, von 10 bis 15 Uhr, vor der [PolKomm-Jahrestagung](https://www.polkomm2021.de/) am 12.02.2020 statt. Es wird sowohl Input- als auch praktische Programmier-Sessions geben. Hier schon mal die vorläufige Agenda:

10:00 - 12:00 Uhr

- #KI, #MachineLearning, #DeepLearning - Buzzwords klären!
- Wie kann ML für die automatisierte Inhaltsanalyse genutzt werden?
- How to start? Data & Software Set-up

12:00 - 13:00 Uhr Lunch Break 
 
13:00 - 15:00 Uhr
 
- Einen Hate-Speech-Classifier bauen - Step by Step
- ML-Modelle evaluieren und bewerten

## Vorbereitung auf den Workshop

Für den Workshop sind keine Programmiervorkenntnisse nötig. Für den praktischen Teil benötigst du lediglich Python auf deinem Computer sowie die nötigen Packages fürs Machine Learning:

- **Python mit Anaconda installieren**: Gehe auf die [Homepage von Anaconda](https://www.anaconda.com/products/individual) und und lade dir unter _Individual Edition_ die Software (Your data science toolkit -> Download) für dein Betriebssystem. Anaconda benutzen wir, damit wir unter Windows- und Mac einfacher programmieren können. Mit Anaconda erhälts du Python, viele vorinstallierte Python-Packages und Programmiersoftware, wie z.B. Jupyter Notebook. In diesem [Tutorial](https://www.youtube.com/watch?v=5mDYijMfSzs "Watch this first tutorial") kannst du dir ansehen, wie du Anaconda unter Windows 10 installierst (bis min 05:07).

[![IMAGE ALT TEXT](http://img.youtube.com/vi/5mDYijMfSzs/0.jpg)](http://www.youtube.com/watch?v=5mDYijMfSzs "Watch this first tutorial")

- **Python-Packages installieren**: Folge dem Tutorial weiter (min 05:08 - 06:41) um zu lernen, wie man Python-Packages installiert. (Dies ist nur eine von mehreren Möglichkeiten.) Versuche die folgenden Packages zu installieren, die wir für die Automatisierte Inhaltsanaylse mit Machine Learning benötigen:

```
conda install pandas
conda install regex
conda install scikit-learn
```

- **Lerne die Programmierumgebung kennen**: Die Software [**Jupyter Notebook**](https://jupyter.org/) macht mit ihrem intuitiven Design Nicht-Programmierer:innen den Einstieg leicht! Jupyter Notebook ist mit Anaconda bereits auf deinem Computer gelandet. Lerne mit Hilfe dieses kurzen [Tutorials](https://www.youtube.com/watch?v=NIGcXjhXNug "Watch this cute tutorial") die Jupyter-Notebook-Programmierumgebung kennen.

[![IMAGE ALT TEXT](http://img.youtube.com/vi/NIGcXjhXNug/0.jpg)](https://www.youtube.com/watch?v=NIGcXjhXNug "Watch this cute tutorial")

- **Packages importieren**: Navigiere dich nun im Menü von Jupyter Notebook in den Workshop-Ordner und versuche das Notebook `requirements.ipynb` auszuführen. Wenn sich alle Packages ohne Fehlermeldung importieren lassen, bist du gewappnet für den Workshop!

### Can't wait!

Wenn du schon mal anfangen möchtest, dich mit **Python** zu beschäftigen, empfehlen wir dir diese [Video-Series](https://www.youtube.com/watch?v=5_QXMwezPJE&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y&index=2 "Watch some videos of one of my favorite ML YouTubers"). Es handelt sich um eine Einführung in die wunderbare Bibliothek `Pandas`, mit der Daten in Python eingelesen und bearbeiten werden können und die aus der Welt des ML und der Data Sciences nicht mehr wegzudenken ist! (Du kannst mit dem 2. Video beginnen). Im Workshop-Ordner `Data Sets` findest du schon eine .csv-Datei mit Tweets, die du als Übung einlesen und untersuchen kannst.

[![IMAGE ALT TEXT](http://img.youtube.com/vi/5_QXMwezPJE/0.jpg)](https://www.youtube.com/watch?v=5_QXMwezPJE&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y&index=2 "Watch some videos of one of my favorite ML YouTubers")


Viel Erfolg und bis bald!
