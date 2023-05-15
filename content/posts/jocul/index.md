---
title: "Jocul în sine"
weight: 1
draft: false
---

osu! este un joc de ritm, fiind bazat pe muzică. 
Are 4 moduri de joc: osu!, osu!taiko, osu!catch și osu!mania.
Cel mai jucat mod este 'osu!'. O să ne concentrăm pe modul 'osu!'.

Muzica jocului nu este aleasă de către echipa de dezvoltare.
Dean "peppy/ppy" Herbert, dezvolatorul jocului, a ales ca jocul să fie "self-maintained", adică comunitatea din jurul jocului să își creeze singur conținutul, singură să își modereze acest conținut, și așa mai departe.
peppy și echipa de moderare vin doar în cazuri speciale.
Astfel, muzica este în principal de origine japoneză.
Sunt și alte limbi, chiar și română, dar predominant sunt melodii japoneze sau compuse de către artisți japonezi.
Motivele pentru acest lucru sunt multe, dar se rezumă la:
* Muzica de origine japoneză este, de obicei, mai variată și mai dinamică;
* Limba japoneză este silabică: sunetele japoneze sunt simple și monosilabice, lucru ce facilitează cântecele japoneze;
* Astfel de jocuri au fost în mare parte de origine japoneză (chiar și osu este teoric de proveniență japoneză) și atrac un public japoneze sau interesat de cultura japoneză.

# Modul de joc osu!

Jocul în sine are în prin-plan trei obiecte, numite și note, pe care trebuie să ducem cursorul mouse-ului și să dăm click (fie cu mouse-ul, fie cu tastatura) în timp cu muzica din fundal: cercul, silder-ul și spinner-ul. Cercul și slider-ul poate lua diferite culori și sunt numerotate în funcție de culoare lor. 

Cercul are două componente: cercul propriu-zis și un alt cerc numit "approach circle". Acest "approach circle" are aceiași culoare ca și cercul principal care îi provine. 
În timp, acest cerc se aproprie de cercul principal, în funcție de o viteză pre-definită. 
Ideia este ca noi să-l "lovim" în momentul în care el este mai mult sau mai puțin conectat de cercul principal. 
Avem o marșă de eroare în care putem da click pe cerc, acesta crescând cu dificultatea aleasă.

![Hit circles](/osu_hitcircles.jpg "Cercul")

Silder-ul este similar cu cercul, cu câteva excepții. 
Cea mai mare și notabilă diferență este faptul că ținem click-ul apăsat pe durata acelui silder, urmărindu-l pe ecran.

![Slider](/osu_slider.jpg "Slider-ul")

Spinner-ul este diferit de cel două obiecte. 
El necesită rotirea cursorului la o viteză aceptabilă în timp ce ținem apăsat click-ul.

![Spinner](/osu_spinner.jpg "Spinner-ul")

Toate aceste note oferă un scor când sunt apăsate și pot scade sau crește acuratețea jucătorului.
Dacă sunt apăsate la timpul potrivit, jucătorul primește 300 de puncte iar acuratețea sa urcă înapoi spre 100%, ori rămâne la 100%.
Altfel, jucătorul primește un scor de 100, 50 sau o ratare, acest lucru depinsând cât de aproape de muzică a fost jucătorul.
Acureatețea jucătorului scade în monentul în care primește un astfel de scor.

Există o bară de viață. Orice scor oferă viață, înafară de o ratare. 
Ratarea scade viață. 
Prea multe ratări va rezulta în viața jucătorului să ajungă la zero, moment în care jucătorul pierde controlul, jocul terminându-se brusc.

Aceste note sunt folosite pentru a crea hărți, numite "beatmaps". 
Aceste hărți sunt create de către jucători și pot trece printr-un proces de verificare a calității. 
Dacă au calitatea dorită, aceasta devin "ranked", adică aceste hărți au un clasament propriu și oferă puncte numite Performance Points sau PP pe scurt.
Aceste puncte sunt folosite pentru plasarea jucătorilor pe un clasament global și unul local pentru țara de proveniență jucătorul.

# Modificatori 

Jocul prezintă modificatori (o să le spun mod/moduri de acum înainte) care alterează orice hartă să fie mai grea sau mai ușoară. 
Acestea modifică câte puncte PP poate primi jucătorul, astfel sunt o parte esențială la nivele mai mari.
Aceste moduri pot fi combinate într-o anumită măsură. Unele moduri anulează alte moduri.
Haideți să trecem în revistă câteva moduri:

**Hard Rock:**
Este un mod ce dorește să crească dificultatea.
Hard Rock cresțe viteza notelor, marșa de eroare pentru un scor perfect și scade dimensiunea notelor.
Pentru modul standard de joc, Hard Rock întoarce harta pe axa X împreună cu modificările de mai sus, pentru a crește dificultatea și mai mult.

**Easy:**
Este un mod care face fix invers ce face Hard Rock.
Scade viteza notelor și marșa de eroare pentru un scor perfect și crește dimensiunea notelor.
Deși numele este "easy", este greșit să crezi că o să facă toate hărțile mai ușoare.
Viteza scăzută face hărțile cu dificultate scăzută spre medie mai ușoare, dar pentru hărțile cu dificulate mare, viteza mică va transforma hărțile fa devini o mare problemă pentru jucători obișnuiți cu vitezele mari.
Acest lucru crește ce-a ce numit *densitatea* hărți.

**Double Time:**
Este un mod care crește viteza melodiei și a notelor. 
Crește și marșa de eroare.

Este unul dintre cele mai folosit mod pentru că oferă cel mai mult pp posibil pentru un FC (un scor fără nicio ratare)

**Half Time:**
Este modul care scade viteza melodiei și a notelor, precum și marșa de eroare.

Nu este folosit foarte mult, decât pentru hărți care la viteza lor normală sunt considerate imposibile pentru un om.

**Hidden:**
Este un mod visual, făcând ca obiectele să apară pentru puțin timp pe ecran, acestea disolvându-se când sunt aproape de-a fi "lovite".
Densitatea și viteza pentru acest mod este un aspect important.

Cu densitatea mică și viteza mare, hidden nu crește foarte mult dificultatea, fiind un bonus mai mult sau mai puțin gratuit, făcând acest mod unul dintre cele mai folosite moduri.
Dacă avem viteza mică și densitatea mică, hidden crește puțin dificultatea.
Dacă avem viteza mică și densitatea mare, hidden crește dificultatea foarte mult.

**NoFail:**
Un mod care elimină viața jucătorului.
Nimic mai mult.
Este în special folosit pentru a exersa anumite aspecte ale jocului.

**Relax:**
Calculatorul va apasă obiectele pe beat-ul muzici.
Jucătorul doar trebuie să miște cursorul la notele unde trebuie.

**Auto:**
Calculatorul joacă harta singur, de la cap la coadă.
Pentru toate hărțile făcute pentru jucători, modul Auto va termina harta cu scor perfect, utilizând orice 

# Demonstrații:

**Fără moduri:**
{{< youtube TnjgvvwSy8A >}}

**Double Time:**
{{< youtube Qc8n4j_mCzk >}}

**Hard Rock:**
{{< youtube KbIAu6bi9O4 >}}
