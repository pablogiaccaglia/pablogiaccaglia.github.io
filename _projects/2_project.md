---
layout: page
title: Software Engineering Project
description: Polimi Software Engineering Project 2020/2021
img:
importance: 2
category: work
---
<h1 id="software-engineering-project-2020-2021">Software Engineering Project 2020-2021</h1>
<p><img src="http://www.craniocreations.it/wp-content/uploads/2019/06/Masters-of-Renaissance_box3D_ombra.png" width=400px height=400px align="right" /></p>
<p><img src="https://img.shields.io/github/last-commit/Calonca/ing-sw-2021-laconca-lodari-giaccaglia?color=red" alt="latest commit">
<img src="https://img.shields.io/badge/license-MIT-green" alt="license"></p>
<p>Maestri del Rinascimento is the final test of <strong>&quot;Software Engineering&quot;</strong> course of <strong>&quot;Computer Science Engineering&quot;</strong> held at Politecnico di Milano (2020/2021).</p>
<p><strong>Teacher</strong>: Pierluigi San Pietro</p>
<p><strong>Group</strong>: SP10</p>
<h4 id="students-">Students:</h4>
<ul>
<li><a href="https://github.com/pablogiaccaglia">Giaccaglia Pablo</a></li>
<li><a href="https://github.com/Calonca">La Conca Alessandro</a></li>
<li><a href="https://github.com/m3f157O">Lodari Gianmarco</a> </li>
</ul>
<h2 id="table-of-contents">Table of Contents</h2>
<ol>
<li><a href="#project-specification">Project specification</a></li>
<li><a href="#implemented-features">Implemented Features</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/communication%20protocol.pdf">Communication Protocol</a></li>
<li><a href="#game-gifs">Game GIFs</a></li>
<li><a href="#game-screenshots">Game Screenshots</a></li>
<li><a href="#software-used">Software Used</a></li>
<li><a href="#copyright-and-license">License</a></li>
</ol>
<hr>
<h2 id="project-specification">Project specification</h2>
<p>The project consists of a Java version of the board game <em>Maestri del Rinascimento</em>, made by Cranio Creations.</p>
<p>You can find the full game <a href="http://www.craniocreations.it/prodotto/masters-of-renaissance/">here</a> and the rules <a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/maestri-rules-en.pdf">here</a>.</p>
<p>The final version includes:</p>
<ul>
<li>initial UML diagram;</li>
<li>final UML diagram, generated from the code by automated tools;</li>
<li>working game implementation, which has to be rules compliant;</li>
<li>source code of the implementation;</li>
<li>source code of unit tests.</li>
</ul>
<h2 id="implemented-features">Implemented Features</h2>
<table>
<thead>
<tr>
<th style="text-align:left">Functionality</th>
<th style="text-align:center">Status</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left">Basic rules</td>
<td style="text-align:center"><a href="https://placeholder.com">☑️</a></td>
</tr>
<tr>
<td style="text-align:left">Complete rules</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/server/model">☑️</a></td>
</tr>
<tr>
<td style="text-align:left">Socket</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/server">☑️</a></td>
</tr>
<tr>
<td style="text-align:left">GUI</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/client/view/GUI">☑️</a></td>
</tr>
<tr>
<td style="text-align:left">CLI</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/client/view/CLI">☑️</a></td>
</tr>
<tr>
<td style="text-align:left">Multiple games</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/server/controller">☑️</a></td>
</tr>
<tr>
<td style="text-align:left">Persistence</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/server/controller">☑️</td>
</tr>
<tr>
<td style="text-align:left">Disconnection resilience</td>
<td style="text-align:center"><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/tree/master/src/main/java/it/polimi/ingsw/server/controller">☑️</a></td>
</tr>
</tbody>
</table>
<h4 id="legend">Legend</h4>
<p>❌ Not Implemented &nbsp;&nbsp;&nbsp;&nbsp; ☑️ Implemented</p>     
<h2 id="usage">Usage</h2>
<h3 id="windows-linux-macos">Windows/Linux/MacOS</h3>
<ol>
<li>Open the command line</li>
<li>Clone the repository</li>
<li>In the repository&#39;s directory, run:<pre><code class="lang-bash"><span class="hljs-selector-tag">java</span> <span class="hljs-selector-tag">-jar</span> <span class="hljs-selector-tag">Maestri</span><span class="hljs-selector-class">.jar</span> <span class="hljs-selector-attr">[mode]</span> <span class="hljs-selector-attr">[port]</span> <span class="hljs-selector-attr">[ip]</span> <span class="hljs-selector-attr">[nickname]</span>
</code></pre>
</li>
</ol>
<p>Modes:</p>
<table>
<thead>
<tr>
<th>Shortcut</th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>-c</code></td>
<td><code>-cli</code></td>
<td>Starts the CLI and connects to server with port</td>
</tr>
<tr>
<td><code>-g</code></td>
<td><code>-gui</code></td>
<td>Starts the GUI and connects to server with port</td>
</tr>
<tr>
<td><code>-s</code></td>
<td><code>--server</code></td>
<td>Starts server with port</td>
</tr>
</tbody>
</table>
<p>Mode argument can be run without further arguments(TCP port &amp; nickname). In such case or in case of mssing arguments these will be asked later. </p>
<h2 id="game-gifs">Game GIFs</h2>
<blockquote>
<p>Note that the following GIFs related to the GUI show the state of the game when it was delivered for evaluation. Due to copyright reasons the assets, which were provided without permission of making them freely available, have been later substituted with ones made by ourselves.</p>
</blockquote>
<h2><p align="center"><b>GUI</b></h2>

<table>
<thead>
<tr>
<th style="text-align:center">Game Turn</th>
<th style="text-align:center">Real time updates</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/gifs/gui1.gif" alt=""></td>
<td style="text-align:center"><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/gifs/gui2.gif" alt=""></td>
</tr>
</tbody>
</table>
<h2><p align="center"><b>CLI</b></h2> 

<p>  <p align= "center">
 <kbd> 
 <img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/gifs/cli.gif" align="center" />
 </kbd>
</p>
<hr>
<h2 id="game-screenshots">Game Screenshots</h2>
<h2><p align="center"><b>CLI</b></h2>

<hr>
<p> <img src="https://raw.githubusercontent.com/pablogiaccaglia/ing-sw-2021-laconca-lodari-giaccaglia/master/screenshots/cli-1.png" align="center" /></p>
<hr>
<p><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/startCLI.png?raw=true" alt="name-of-you-image"></p>
<hr>
<p><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/boardCLI.png?raw=true" alt="name-of-you-image"></p>
<hr>
<p><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/cardshopCLI.png?raw=true" alt="name-of-you-image"></p>
<hr>
<p><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/marketCLI.png?raw=true" alt="name-of-you-image"></p>
<hr>
  <h2><p align="center"><b>GUI</b>;</h2>

<blockquote>
<p>Note that the following screenshots related to the GUI show the state of the game when it was delivered for evaluation. Due to copyright reasons the assets, which were provided without permission of making them freely available, have been later substituted with ones made by ourselves.</p>
</blockquote>
<hr>
<p><img src="https://raw.githubusercontent.com/pablogiaccaglia/ing-sw-2021-laconca-lodari-giaccaglia/master/screenshots/gui-1.png" align="center" /></p>
<hr>
<p><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/boardGUI.png?raw=true" alt="name-of-you-image"></p>
<hr>
<p><img src="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/deliverables/final/cardshopGUI.png?raw=true" alt="name-of-you-image"></p>
<hr>
<p><img src="https://raw.githubusercontent.com/pablogiaccaglia/ing-sw-2021-laconca-lodari-giaccaglia/master/screenshots/gui-2.png" align="center" /></p>
<hr>
<p><img src="https://raw.githubusercontent.com/pablogiaccaglia/ing-sw-2021-laconca-lodari-giaccaglia/master/screenshots/gui-3.png" align="center" /></p>
<hr>
<p><img src="https://raw.githubusercontent.com/pablogiaccaglia/ing-sw-2021-laconca-lodari-giaccaglia/master/screenshots/gui-4.png" align="center" /></p>
<ul>
<li>We implemented a 3D gui based on a simplified model of the server&#39;s state machine. The user can freely see their board, using W and S to cycle between Board view, Market view, and Frontal view, which covers every game component. While looking from the Frontal view, the player can use D and S keys to rotate around the table, with 90 degree steps. Both the CLI and GUI implement real time updates on the game state. Common elements, such as CardShop and ResourceMarket are shared between all players, each players sees them in front of their board but they are actually synchronized</li>
</ul>
<h2 id="testing">Testing</h2>
<ul>
<li><p>All unit test have been automated when possible. For some network functionalities it has been necessary to perform some manual QA instead
of a mock test , for which it would have required too many stubs (being a stateful protocol) so we choose
manual Quality Assurance.</p>
</li>
<li><p>All the model classes have been extensively covered, along with most of the controller&#39;s classes when possible. Some functionalities regarding
production output conversion and leader activation do not have an automated test, but our manual tests led us to assert that the functionalities
implemented are stable in all cases.</p>
</li>
<li><p>Clicking repeatedly during the drag and drop action may cause issues.</p>
</li>
<li><p>All the unit test have been run before each commit</p>
</li>
</ul>
<h2 id="software-used">Software Used</h2>
<p><strong>sequencediagram.org</strong> - sequence diagrams</p>
<p><strong>Draw.io</strong> - UML diagrams</p>
<p><strong>Intellij IDEA Ultimate</strong> - main IDE </p>
<h2 id="copyright-and-license">Copyright and License</h2>
<p>Maestri del Rinascimento is copyrighted 2020.</p>
<p>Licensed under the <strong><a href="https://github.com/Calonca/ing-sw-2021-laconca-lodari-giaccaglia/blob/master/LICENSE">MIT License</a></strong>.
You may not use this software except in compliance with the License.</p>
