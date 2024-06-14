# The-Simplest-Ways-to-Handle-HTML-Includes-
The Simplest Ways to Handle HTML Includes 

fist primeiro crie se footer e crie uma unica pagina footer.html  depois de estilizar 

The simplest ways to deal with HTML include 

Using iframe, first create footer file footer.html in index.html between <body></body> tag

Paste this code in the middle of the body and your pages will be ready with the footer appearing

<iframe src="footer.html" onload="this.insertAdjacentHTML('afterend', (this.contentDocument.body||this.contentDocument).innerHTML);this.remove()"></iframe>
