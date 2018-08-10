# Willkommen zum Java Guide der FOI 12

## Inhaltsverzeichnis

- [Eine Einführung](#eine-kurze-einführung)
- [Die JVM](#die-jvm)
- [Programme die wir benötigen](#programme-die-wir-benötigen)
- [Wie geht es weiter ?](#wie-geht-es-weiter-)
- [Anhang](#anhang)
---


## Eine kurze Einführung

### Wie lerne ich Programmieren bzw. Java ?
---
Um die Konzepte der Programmierung zu verstehen muss man einmal etwas weiter ausholen. Dir muss klar sein das, dass einfache lesen des Guides dich nicht zum Master of the Universe macht. Programmieren lernt man daDurch dass man programmiert. Learning by doing, ist dass Stichwort. 

Also los gehts !

---

### Ein paar generelle Sachen zur Programmierung
---
Wie auch in unserer Sprache gibts es verschiedene Programmiersprachen. Es gibt z.B C, C++, Python, Java usw.
Der große vorteil liegt aber darin, wenn Du eine Sprache kannst, hast Du es leicht weitere zu erlernen. Da die Konzepte gleich bleiben, es ist völlig egal ob ich eine Software in Java oder C++ schreibe. Die Programmiersprache ist nur das Werkzeug. Natürlich brauchen spezielle Programme auch spezielle techniken. Du kannst z.B schlecht einen Treiber für einen USB Stick mit Java schreiben dafür wird eher C verwendet, da Java nicht sehr Hardware nah ist, aber dazu später mehr.

---

### Worin unterscheiden sich die Programmiersprachen ?
---
Es gibt 3 Typen von Programmiersprachen, die ***Compiler-,***  ***Interpreter-*** und die sogenannten ***Bytecodesprachen***.

Hä was ?

---

#### Compilersprachen

Die Compilersprachen sind vereinfacht gesagt, Sprachen die vom Computer in Maschinencode umgewandelt werden, also das typische 
```c
01001101 01100001 01101100 01110100 01100101 00100000 01101001 01110011 01110100 00100000 01110011 01100101 01111000 01111001 
```

**Vorteile**: Sehr schnell, Sehr Hardwarenah, Sehr geil  
**Nachteile**: Fehler werden meistens erst spät erkannt, Es muss sehr viel auf die Hardware geachtet werden, Meistens nicht Plattformübergreifend

Compilersprachen sind z.B **C**, **C++** oder auch **Assembler**.

So sieht es im Prozess aus:

![Compilter Image](https://www.elektronik-kompendium.de/sites/com/bilder/17052311.gif)

Der Prozess ist hier aber sehr **vereinfacht**.

---

#### Interpretersprachen
Wie der Name schon sagt werden diese Sprache Interpretiert. Doch was heißt das ?

Du hast eine Datei, die wird von einem Programm eingelesen und ausgeführt. Das spart Zeit, da man diese Datei nicht noch compileren muss. 

**Vorteile**: kein Compiler ist nötig, Plattformunabhängig, Fehler werden bei der Laufzeit erkannt  
**Nachteile**: Langsamer als Compilersprachen, Nicht Hardwarenah

Interpretersprachen sind z.b **Ruby**, **Python**, **JavaScript** oder **PHP**.

Der Prozess sieht etwa so aus:

![Intepreter Image](https://www.elektronik-kompendium.de/sites/com/bilder/17052312.gif)

Aber auch hier gilt, sehr **vereinfacht**.

---
#### Bytecodesprachen

Kommen wir zur letzen Sprachenart, die Bytecodesprachen. Bei den ***Bytecodesprachen*** handelt es sich um eine mischung aus ***Compiler-*** und ***Interpretersprachen***.
Die beiden Techniken werden sozusagen vereint. Dazu gehört aber noch eine VM *(Virtual Machine)*, die VM übernimmt das Compileren und Ausführen.

Die Dateien werden am anfang Interpretiert und in Bytecode umgewandlet. Danach wird dieser Bytecode von der VM compiliert und ausführbar gemacht.

Jetzt ist es aber so, hat man das Ausführbareprogramm aber nicht die VM, kann das Programm nicht ausgeführt werden. Also muss man diese VM installiert haben um damit zuarbeiten und Programme auszuführen.

**Vorteile**: Plattformunabhängig, meistens schneller als Interpretersprachen  
**Nachteile**: Langsamer als Compilersprachen, Nicht Hardwarenah

Bytecodesprachen sind z.b **Java**, oder **C#**.

---

## Die JVM

---

Hier erkläre ich kurz die JVM. Da wir gelernt haben dass Java eine Bytecodesprache ist, benötigt sie auch eine VM, und jetzt ratet mal was JVM heißt.  

Richtig, *Java Virtual Machine* kurz ***JVM***.
Darin wird unser gesamter Javacode verarbeitet und bei bedarf ausgeführt.

Der Aufbau der ***JVM***:
![JVM image](https://upload.wikimedia.org/wikipedia/commons/d/dd/JvmSpec7.png)

*Sieht kompliziert aus. Ist es auch, wir kommen darauf später zurück.*

---

## Programme die wir benötigen

---

### Die JVM bzw. das JDK
Wie gesagt benötigen wir um Java zu schreiben die JVM, aber auch zusätzliche Programme wie *JavaDoc*. Ich gehe darauf später näher ein. Wir laden uns das JDK (Java Development Kit) herunter. Ihr könnt es euch [hier](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) herunterladen. Wählt eure Plattform aus und installiert das JDK.


### Einen Editor oder eine IDE
Natürlich brauchen wir einen Editor, um unsere Quelltexte zu schreiben. Ich benutze dafür [Visual Studio Code](https://code.visualstudio.com). Einen sehr flexiblen und schnellen Code Editor. Ihr könnt ihn euch [hier](https://code.visualstudio.com/download) runterladen. Natürlich könnt Ihr auch andere Editoren benutzen. Alternativen sind [Atom](https://atom.io), [Sublime Text](https://www.sublimetext.com/) und [Notepad++](https://notepad-plus-plus.org/).

Wenn Ihr lieber eine IDE (Integrated Development Environment) benutzen wollt empfehle ich ***Intellij*** oder ***Eclipse***.

Ich schreibe für alle drei Programme (VSCode, IntelliJ und Eclipse) einen Guide. Guck dafür weiter unten.

---

## Wie geht es weiter ?

Nun fragst Du dich sicher, **Und jetzt ?**
Im nächsten Kapitel, werden wir nun endlich Programmieren. Klick dafür [hier](/docs/1-Unser-Erstes-Programm.md).

Eine weiter Sache die von Vorteil wäre ist, das Du Git lernst. Es ist ganz einfach klick dafür [hier](https://github.com/FOI-12/Getting-Started). Lies es dir in Ruhe Durch, Du findes Git im Abschnitt **Informationen** (Ganz oben).


---

## Ressorcen zum eigenständigen Lernen

### Codeacedemy

[Codeacedemy](https://www.codecademy.com/) ist eine kostenlose, interaktive Lernplattform auf welcher ihr Java lernen könnt. Sie hilf euch die **Grundlagen** einer Sprache, sowie des allgemeinen Programmieren zu erlernen. Zu beachten ist jedoch das es nur eine Hilfe ist, und nicht die Praxis ersetzt.

---

#### Anhang
<p style="font-size:80%;">Die Bilder kommen von https://www.elektronik-kompendium.de und alle Rechte gehen dort auch hin.<p/>
