
<h1 style="color:Navy;"><a id="Übe"><b>Stride Aktivitäten Krull+Tiedemann</b></a></h1>
<p>Informatik bei Herrn Buhl, 4. Halbjahr Qualifikationsphase</p>

<p><a href="https://marliskrull.github.io/Stundenprotokoll_2/">Hier geht's zu unserem Stundenprotokoll!</a></p>
 
<h1 style="color:CadetBlue;"><b>Ladybug Quest</b></h1>
<p>Bitte entnehmen Sie unsere Räuber-Beute Simulation "Ladybug Quest" dem Informatikordner auf iSurfStormarn.</p>
    
<h2 style="color:Navy;">Gliederung</h2>

<ul style="color:CadetBlue;">
      <li><a href="#Bio">1. Biologische Grundlagen </a></li>
      <li><a href="#Lot">1.1 "Lotka-Volterra-Regeln"</a></li>
      <li><a href="#Sim">2. Simulationsentwicklung</a></li>
      <li><a href="#Ide">2.2 Ideen</a></li>
      <li><a href="#Imp">2.3 Implementierung</a></li>
      <li><a href="#Wei">3. Weitere Entwicklungsideen</a></li>   
    </ul>

<hr>

<h2 style="color:Navy;"><a id="Bio">Biologische Grundlagen</a></h2>

<p> 

<h3 style="color:Navy;"><a id="Lot">"Lotka-Volterra-Regeln"</a></h3>

<p> Die Lotka-Volterra-Regeln, auch Lotka-Volterra-Gesetze oder nur Volterra-Regeln genannt, umfassen drei Regeln zur quantitativen Beschreibung der Populationsdynamik in Räuber-Beute-Beziehungen. </p>

<ul style="color:CadetBlue;">
<li>Erste Lotka-Volterra-Regel (Periodische Populationsschwankung): Die Populationsgrößen von Räuber und Beute schwanken periodisch. Dabei folgen die Schwankungen der Räuberpopulation phasenverzögert denen der Beutepopulation. Die Länge der Perioden hängt von den Anfangsbedingungen und von den Wachstumsraten der Populationen ab.</li>
<li>Zweite Lotka-Volterra-Regel (Konstanz der Mittelwerte): Die über genügend lange Zeiträume gemittelten Größen (Mittelwert) der Räuber- bzw. Beutepopulation sind konstant. Die Größe der Mittelwerte hängt nur von den Wachstums- und Rückgangsraten der Populationen, nicht aber von den Anfangsbedingungen ab.</li>
<li>Dritte Lotka-Volterra-Regel (Störung der Mittelwerte): Werden Räuber- und Beutepopulation gleichermaßen proportional zu ihrer Größe dezimiert, so vergrößert sich kurzfristig der Mittelwert der Beutepopulation, während der Mittelwert der Räuberpopulation kurzfristig sinkt.</li>
</ul>

<p><img src="Images/lotka-volterra-kurve.gif" alt="Veranschaulichung der Lotka-Volterra-Regeln" 
style="width:400px;height:250px;border:0;"></p>

<p>Die Lotka-Volterra-Regeln sind strenggenommen nur unter Beachtung ihrer selten erfüllten Voraussetzungen anwendbar. Trotzdem sind sie in der praktischen Ökologie von großer Bedeutung, weil sich zeigt, dass sie auch bei komplexeren Nahrungsbeziehungen und schwankenden Umweltfaktoren durchaus noch brauchbare Abschätzungen liefern.</p>
<p><a href="https://de.wikipedia.org/wiki/Lotka-Volterra-Regeln"> Quelle </a> </p>
<p>Für weitere Informationen zu den Lotka-Volterra-Regeln, siehe: <br> 
<a href="https://de.wikipedia.org/wiki/Lotka-Volterra-Regeln">https://de.wikipedia.org/wiki/Lotka-Volterra-Regeln</a></p>

<h2 style="color:Navy;"><a id="Sim">Simulationsentwicklung</a></h2>

<h3 style="color:Navy;"><a id="Ide">Ideen</a></h3>

<h3 style="color:Navy;"><a id="Imp">Implementierung</a></h3>

<h4 style="color:CadetBlue;">Die Laus-Klasse</h4>

<p><img src="Images/Laus1.jpg" style="width:776px;height:679px;border:0;"></p>

<p>Die act-Methode der Laus-Klasse enthält 6 Methoden, die im Folgenden detailliert beschrieben werden. <br>
Um das Geschlecht der Laus festzulegen, wird eine Variable "istWeiblich" vom Typ boolean erstellt. Diese wird im Constructor zu einer 50%-igen Wahrscheinlichkeit entweder auf true oder auf false gesetzt. Die Laus ist also entweder weiblich, oder nicht.</p>


<p><img src="Images/Laus2.jpg" style="width:780px;height:110px;border:0;"></p>
<p><img src="Images/Laus3.jpg" style="width:775px;height:375px;border:0;"></p>
<p><img src="Images/Laus4.jpg" style="width:777px;height:511px;border:0;"></p>
<p><img src="Images/Laus5.jpg" style="width:775px;height:183px;border:0;"></p>
<p><img src="Images/Laus6.jpg" style="width:777px;height:200px;border:0;"></p>
<p><img src="Images/Laus7.jpg" style="width:776px;height:163px;border:0;"></p>

<h4 style="color:CadetBlue;">Die Käfer-Klasse</h4>

<h4 style="color:CadetBlue;">Die Pheromone-Klasse</h4>

<h4 style="color:CadetBlue;">Der Graph</h4>


<h2 style="color:Navy;"><a id="Wei">Weitere Entwicklungsideen</a></h2>

<hr>

<p style="color:CadetBlue;"><a href="#Übe">zum Seitenanfang</a></p>
