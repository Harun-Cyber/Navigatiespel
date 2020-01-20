<img src="Media Semester 2/Portfolio/DEV/Website foto's/navigatie.png" width="250px" height="200px" style="float: right;">	
							<h3>Wat heb ik gedaan</h3>
							<p>Ik heb een Navigatiespel gemaakt waarbij je als je de gele blokken raakt je dan ook geredirect wordt naar een ander deel van mijn website.</p>
                            <p>Ik heb ook een andere versie gemaakt met meerdere levels. Elke level is een gloed nieuw spel.</p>
							<h3>Hoe heb ik het gemaakt</h3>
							<p>Om mee te beginnen heb ik een paar dingen nodig. Ik heb een manier nodig om het spelerobject te volgen, ik heb een gameloop nodig om de logica bij te werken en op het scherm te tekenen, en ik moet omgaan met gebruikersinvoer.</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie1.png" width="1100px" height="300px" style="float: right;">
							<p>Ik heb eerst de canvas die ik gemaakt heb in de HTML link opgeroepen in Javascript d.m.v. de ID ervan op te roepen en ik heb deze ook vervolgens een context gegeven met width en height. Ik heb vervolgens een player klasse gemaakt met alle functionaliteiten erin die een player nodig zou moeten hebben.</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie2.png" width="1100px" height="200px" style="float: right;">
							<p>Ik heb een array gemaakt met alle key pushes erin en twee variabelen die kijken naar de gravity van de speler en de friction ervan. Er is ook een array met de coins. Daarbij gebruik ik de push methode om ervoor te zorgen dat de dimensies die te zien zijn in de arrays ook tevoorschijn komen in de canvas. Dit is ook gedaan met de boxes die de platformen moeten voorstellen</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie3.png" width="1100px" height="400px" style="float: right;">
							<p>Dit zijn de formules die ik gebruikt heb om ervoor te zorgen dat de speler kan bewegen d.m.v. de key push events te gebruiken. En de laatste twee regels zijn gebruikt om ervoor te zorgen dat je de snelheid en de gravity van de speler bij de movement toe te voegen van de speler kunt aanpassen.</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie4.png" width="1100px" height="300px" style="float: right;">
							<p>Hier maak ik de coins aan in mijn code door deze in te kleuren met de kleur geel. Hierin heb ik ook een loop gebruikt zodat je de coins ook kunt zien in mijn code. Zonder de loop kan je de coins niet meer zien. Vervolgens roep ik mijn methode ColissionChecker opgeroepen die kijkt naar de collision tussen speler en object. Als de speler het object raakt wordt hij geredirect naar een HTML pagina. Dit is gedaan d.m.v. window.location toe te voegen aan mijn code.</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie5.png" width="1100px" height="400px" style="float: right;">
							<p>Hier laat ik de platformen zien maar deze keer is de code anders. In plaats van dat je naar een andere pagina gaat als je de platformen raakt, stop je als je de platformen raakt. Als je een platform aanraakt wordt je movement 0.</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie6.png" width="1100px" height="500px" style="float: right;">
							<p>Deze methode heb ik gemaakt om ervoor te zorgen dat twee objecten tegen elkaar gaan controleren, de player en een box(platformen). Dit doe ik door te controleren of ze elkaar kruisen. Als ze elkaar kruisen, moeten ze tegen elkaar botsen. Omdat ik aan een platformgame werk, heb ik nog een stukje informatie nodig, vanuit welke richting de speler naar het object botst. Daarvoor heb ik een aantal if statements en formules gemaakt die kijkt naar de richtingen vanuit waar de speler tegen het objecxt botst.</p>
							<img src="Media Semester 2/Portfolio/DEV/Codes afbeeldingen/navigatie7.png" width="1100px" height="200px" style="float: right;">
							<p>Hier heb ik keyboard events aangemaakt, ik wilde de keyboard events oorspronkelijk in de canvas element doen. Maar dit werkte niet dus heb ze gebind aan de body.</p>
							<h3>Wat heb ik hiervan geleerd</h3>
							<p>Om met een Navigatiespel te beginnen heb ik heel veel geleerd van Javascript. Ik heb weer een beetje kennis van wiskunde meegekregen sinds ik de afgelopen jaren weinig tot geen wiskunde meer heb gehad of gebruikt.</p>
							<p>Het was zeer leerzaam om alle functionaliteiten te leren van Javascript en ook om formules toe te passen in Javascript omdat ik niet eerder een platformspelletje heb gemaakt in Javascript.</p>
							<h3>Feedback</h3>
							<p>Als feedback heb ik te horen gekregen van Eric dat ik wellicht het Navigatiespel kon uitbreiden door er verschillende functionaliteiten erbij toe te voegen.</p>
							<a href="sidescroller.html" class="button special">Klik hier voor mijn Navigatiespel van mijn website</a>
                            <a href="Sidescroller-Game/index.html" class="button special">Klik hier voor mijn Navigatiespel waar je meerdere levels in hebt</a>