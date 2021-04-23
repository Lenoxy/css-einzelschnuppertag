<!-----
NEW: Check the "Suppress top comment" option to remove this info from the output.

Conversion time: 1.323 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β29
* Fri Apr 23 2021 00:53:00 GMT-0700 (PDT)
* Source doc: Python Schnuppertag
* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 3.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# Programmieren mit Python

CSS Versicherung, Schnuppertag




# Turtle

Für das Programmieren von Python brauchen wir die Entwicklungsumgebung (IDE) PyCharm. Um ein neues Python File zu erstellen muss man den Projektordner _untitled _mit rechte Maustaste klicken → _New_ → _Python File_. Für das File als Name den Name der Aufgabe geben z.B.: _Aufgabe1_. 

Für das Programm ist auch noch ein ‘Turtle’ zu verwenden. Um es zu erstellen, muss man es noch importieren mit der Zeile _import turtle_. Nach dem Import muss das ‘Turtle’ in eine Variable gespeichert sein. Die Variable darf ein frei gewählter Name haben, z.B.:  ‘_Alex = turtle.Turtle()_’ oder ‘_Leo = turtle.Turtle()_’.

Mit einer Turtle in Python können Strukturen gezeichnet werden. Dafür braucht es einige wichtige Befehle. Die Befehle müssen immer mit der erstellten Variable verknüpft werden z.B.: _Leo.fd(90)_.


<table>
  <tr>
   <td><strong>Befehl</strong>
   </td>
   <td><strong>Bezeichnung</strong>
   </td>
  </tr>
  <tr>
   <td>forward(90) oder fd(90)
   </td>
   <td>Lässt die Schildkröte 90 Pixel nach vorne fahren.
   </td>
  </tr>
  <tr>
   <td>backward(50) oder bk(90)
   </td>
   <td>Lässt die Schildkröte 50 Pixel nach hinten fahren.
   </td>
  </tr>
  <tr>
   <td>right(90) oder rt(90)
   </td>
   <td>Die Schildkröte dreht sich 90 Grad nach rechts.
   </td>
  </tr>
  <tr>
   <td>left(90) oder lt(90)
   </td>
   <td>Die Schildkröte dreht sich 90 Grad nach links.
   </td>
  </tr>
  <tr>
   <td>dot(20)
   </td>
   <td>Macht einen Punkt mit 20 Pixel durchmesser.
   </td>
  </tr>
</table>


Mit diesen Grundsätzlichen Befehlen solltest du die Schildkröte bewegen können.

Damit dein Programm nach dem Zeichnen sich nicht sofort beendet, soll immer in der letzte Zeile turtle.done() stehen.

Um das Programm zu ausführen: Rechtsklick auf dein File → Run ‘_file_’.


## Aufgabe 1

Zeichne ein Rechteck.


## Aufgabe 2

Zeichne ein Haus.


## Aufgabe 3 

Zeichne einen Stern.



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



<table>
  <tr>
   <td>color(‘blue’)
   </td>
   <td>Ändert die Farbe auf Blau
   </td>
  </tr>
  <tr>
   <td>penup()
   </td>
   <td>Lässt die Schildkröte nicht mehr Zeichnen, auch wenn sie herumfährt.
   </td>
  </tr>
  <tr>
   <td>pendown()
   </td>
   <td>Die Schildkröte zeichnet wieder.
   </td>
  </tr>
  <tr>
   <td>shape(‘arrow’)
   </td>
   <td>Ändert die Form der Schildkröte auf ein Pfeil.
   </td>
  </tr>
</table>


Falls du noch mehr Funktionen kennenlernen möchtest, besuche folgende Seite: \
[http://interactivepython.org/runestone/static/IntroPythonTurtles/Summary/summary.html](http://interactivepython.org/runestone/static/IntroPythonTurtles/Summary/summary.html)

[https://www.tutorialspoint.com/turtle-programming-in-python](https://www.tutorialspoint.com/turtle-programming-in-python)


## Aufgabe 4

Zeichne zwei Vierecke mit einer Schildkröte.


## Variablen mit Zahlen

Variablen kannst du nicht nur für deine ‘Turtle’ benutzen, sondern auch für Zahlen. Wenn du eine Variable erstellst, musst du immer sein Wert auch mitgeben z.B.: ‘_x = 5_’ oder ‘_x = 123_’. 

Der Wert von Variablen kann überschrieben werden. Zum Beispiel, wenn man _x = x + 1_ eingibt, wird der Wert um 1 erhöht.


## While Schleife

Eine While Schleife wiederholt seinen Inhalt. Dabei kannst du der While Schleife sagen, wie oft die Schleife den Code wiederholen soll.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


Wichtig ist dass der Code, der Wiederholt werden soll (_doSomething()_ in diesem Beispiel) Mit einem Tab eingerückt ist (Sich weiter rechts befindet als _while …_)

Wenn du wieder Code schreiben möchtest, der sich ausserhalb der Schleife befindet, schreibe dies wieder auf der höhe vom _while _Statement.


## Aufgabe 5

Mache ein Viereck, benutze aber so wenig Code wie möglich.


## Aufgabe 6

Zeichne einen Kreis.

Tipp: Setze eine Variable, die deine while Schleife 360 Mal wiederholen lässt.


## Bonusaufgabe

Zeichne eine Spirale.


## If / Else

Dies heisst so viel wie “Wenn / Sonst”. Also mit “If” kann gewisser Code ausgeführt werden, aber NUR Wenn ein gewisse Kondition zutrifft. Wenn dir dies etwas kompliziert vorkommt, hier ein praktisches Beispiel:

Falls _x_ größer als 8 ist, soll der Pointer (die Turtle) um 100 Pixel nach vorne bewegt werden.

Um alle anderen fälle “abzufangen” benutzen wir das _else_ Statement. 


## Aufgabe 7

Geht die Turtle vorwärts oder rückwärts im rechten Beispiel?


## Konsole

In der Konsole kann mit dem Befehl print(Message) eine Nachricht in der Konsole ausgegeben werden. Dabei dürfen die Apostrophe nicht vergessen werden. Dieser Text wird dann in der Konsole ausgegeben.


## 

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")
Aufgabe 8

Speichere dein Alter in einer Variabel. \
Prüfe ob du unter oder über 18 Jahre alt bist.

Gib dann je nach Fall aus, ob du bereits Auto fahren darfst.

