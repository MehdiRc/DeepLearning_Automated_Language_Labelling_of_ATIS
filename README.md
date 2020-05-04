
<h1 style="text-align: center;">Automated Language Labelling of Airline Travel Information System (ATIS) </h1>
<h4><code>TER de Deep Learning </code></h4>
<p><strong style="color: #000;"></strong></p>
Mehdi Chakhchoukh, Quentin Lemasson
<hr>

<p>
  <strong style="color: #000;"> Introduction et But du projet: </strong>
Le but de ce projet est de faire de l'étiquetage de séquence. C’est-à-dire d’étiqueter les mots de phrases du langage et ainsi associer à chaque mot une étiquette selon le contexte de la phrase. 

</p>


<hr>

<p>
  <strong style="color: #000;">Le Dataset: </strong>

Nous travaillons avec le corpus ATIS, qui est un corpus des années 90 dédié à la compréhension de la parole.

Notre travail donc sera d’étiqueter, et ainsi d’identifier certaines caractéristiques de Vols à partir des phrases qui nous sont présentées ; comme par exemple identifier l’heure de départ d’un vol et lui attribuer l’étiquette « B-depart_time ».

Voici un exemple de phrase étiquetée :
</p>

![ImageEx](img/1.PNG?raw=true "")
<hr>

<p>
  <strong style="color: #000;">Notre sollution</strong>: Nous avons d'abord utilisé des réseaux neuronaux récurrents qui sont particulièrement efficace si utilisé sur des données séquentielles (comme le langage humain). Puis nous avons eu l'idee de faire un hybride entre un LSTM et un Perceptron multicouche avec un feature  vector ciblé.
</p>

 <p>
  <strong style="color: #000;">Nos Resultats</strong>:
  
![ImageEx](img/1.PNG?raw=true "")
</p>
