**MIRTE** lite 
==========================

Les 1: Kennismaken met robots


.. revealjs-section::
   :data-background-image: _static/media/mirte-lite/mirte-lite-les1/MIRTE-ingekleurd-op-lijn.png


**Doel & Uitleg**
--------------------
.. container:: smaller70

   Door middel van quizvragen, filmpjes en opdrachten leer je waarom een robot een robot is, leer je uit welke onderdelen een robot bestaat en wat voor soorten robots er zijn. 


.. container:: half smaller50
   
   Ga met je muis over het vraagteken heen.

.. container:: half smaller40

   .. raw:: html

      <div class="popup">
       <img src="_static/media/mirte-lite/mirte-lite-les1/information-icon_1.png" style="width:auto; height:100px;">
       <span class="popuptext">Op sommige pagina's kom je dit vraagteken tegen. Wanneer je hier met je muis overheen gaat, krijg je extra informatie over de vraag of opdracht die je aan het maken bent. Dit werkt ook bij een aantal afbeeldingen in deze les. Ben je een ouder, begeleider of docent? Dan kun je de informatie bij de afbeeldingen en vraagtekens gebruiken voor achtergrond informatie of voor het voorbereiden van jouw les.</span>
      </div>


**Wat is een robot?**
--------------------

.. container:: smaller70

   Een robot is een programmeerbare machine die zelfstandig een serie van taken kan uitvoeren en kan reageren op zijn omgeving.

.. raw:: html

   <div class="popup">
   <img src="_static/media/mirte-lite/mirte-lite-les1/information-icon_1.png" style="width:auto; height:40px;">
   <span class="popuptext smaller40">Wetenschappers zijn het er soms niet over eens met elkaar, maar eenvoudig gezegd is een robot een programmeerbare machine die zelfstandig taken uitvoert. Maar volgens deze definitie zouden een pinautomaat en een koffiezetapparaat ook robots zijn. Wat deze apparaten niet kunnen, is reageren op hun omgeving. Robots kunnen dat wel. Ze zijn vaak uitgerust met sensoren zoals camera’s, thermometers en lichtmeters om zo nodig hun taken aan te passen op basis van wat de sensoren gemeten hebben.</span>
   </div>

.. raw:: html

    <!DOCTYPE html>
    <html>
    <head>
    <style>

    .column {
    flex: 1;
    padding: 5px;
    }

    .row {
    display: flex;
    justify-content: center;
    }
    </style>
    </head>
    <body>

    <div class="row">
    <div class="column">
    <div class="popup">
       <img src="_static/media/mirte-lite/mirte-lite-les1/spot-climbs-stairs.jpg" style="width:auto; height:200px;">
       <span class= "smaller40 popuptext">Dit is Spot, een robot die de omgeving kan scannen en in kaart kan brengen.</span>
      </div>
    <div style="clear: both;"></div>
    
    <div class="smaller50">Spot - Boston Dynamics</div>

    </div>

    <div class="column">
    <div class="popup">
       <img src="_static/media/mirte-lite/mirte-lite-les1/lely-grass-robot.jpg" style="width:auto; height:200px;">
       <span class= "smaller40 popuptext">De Lely Exos is een robot die gras kan maaien en dit gras dan gelijk aan de koeien in de stal kan voeren. Met behulp van sensoren zorgt de robot ervoor dat hij tijdens het grasmaaien niet in de sloot valt en het gras op een perfecte afstand van het hek bij de koeien aflevert.</span>
      </div>
    <div style="clear: both;"></div>

    <div class="smaller50">Exos (gras maai- en voerrobot) - Lely</div>

    </div>

    <div class="column">
    <div class="popup">
       <img src="_static/media/mirte-lite/mirte-lite-les1/Dyson-360-Vis-Nav-1-770x437.jpg" style="width:auto; height:200px;">
       <span class= "smaller40 popuptext">Een robotstofzuiger gebruikt een sensor om een plattegrond van het huis te maken en zorgt er vervolgens voor dat elk hoekje in de kamer schoongemaakt wordt.</span>
      </div>
    <div style="clear: both;"></div>

    <div class="smaller50">Robotstofzuiger - Dyson</div>

    </div>

    </body>
    </html>


**Wel of geen robot?**
--------------------

.. container:: smaller70
   
   Op welke afbeeldingen is een robot te zien? Er zijn twee antwoorden goed.

.. raw:: html

   <div class="grid-container">
        <button class="button4"><img src="_static/media/mirte-lite/mirte-lite-les1/wasmachine.jpg"; style="width:auto; height:150px"></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/industrial-robotic-arm.jpg"; style="width:auto; height:150px"></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/pepper-zorgrobot.jpg"; style="width:auto; height:150px"></button>
        <button class="button4"><img src="_static/media/mirte-lite/mirte-lite-les1/airfryer.jpg"; style="width:auto; height:150px"></button>
   </div>

.. raw:: html

   <div class="popup">
   <img src="_static/media/mirte-lite/mirte-lite-les1/information-icon_1.png" style="width:auto; height:40px;">
   <span class="popuptext smaller40">Vraag je af: 1. Is het programmeerbaar, waardoor het zelfstandig taken uit kan voeren? 2. Kan het reageren op zijn omgeving? Als je deze twee vragen kunt beantwoorden met 'ja', dan is het een robot!</span>
   </div>

    
**Waar bestaat een robot uit?**
--------------------

.. container:: smaller70
   
   De robot die we tijdens de volgende workshops gaan gebruiken bestaat uit 6 elementen.

.. raw:: html

    <!DOCTYPE html>
    <html>
    <head>
    <style>

    .column {
    flex: 1;
    padding: 5px;
    }

    .row {
    display: flex;
    justify-content: center;
    }
    </style>
    </head>
    <body>

    <div class="row">
    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/frame.png" style="width:auto; height:150px;">
        <span class="popuptext smaller40">Het frame zorgt ervoor dat alle onderdelen bij elkaar gehouden worden en dat de robot tegen een stootje kan.</span>
        </div>
    <div style="clear: both;"></div>
    
    <div class="smaller50">frame</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/battery-pack.png" style="width:auto; height:150px;">
        <span class="popuptext smaller40">De krachtbron zorgt ervoor dat de robot energie krijgt om te bewegen. MIRTE lite gebruikt batterijen als krachtbron.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">krachtbron</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/obstacle-sensor.png" style="width:auto; height:150px;">
        <span class="popuptext smaller40">Met behulp van sensoren kan de robot zijn omgeving waarnemen. Bijvoorbeeld door obstakels te herkennen met de obstakelsensor.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">sensoren</div>

    </div>

    </body>

    <head>
    <style>

    .column {
    flex: 1;
    padding: 5px;
    }

    .row {
    display: flex;
    justify-content: center;
    }
    </style>
    </head>
    <body>

    <div class="row">
    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/motor-driver.png" style="width:auto; height:150px;">
        <span class="popuptext smaller40">De motor driver controleert de energie van de krachtbron. Op basis van de informatie van de sensoren zorgt de motor driver ervoor dat de motoren de juiste hoeveelheid energie krijgen om de motoren op de juiste manier te laten draaien (vooruit, achteruit, sneller, langzamer). </span>
        </div>
    <div style="clear: both;"></div>
    
    <div class="smaller50">motor driver</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/motor.png" style="width:auto; height:150px;">
        <span class="popuptext smaller40">De motoren kunnen een ander onderdeel in beweging brengen. Ze kunnen bijvoorbeeld de wielen laten draaien.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">motoren</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/wheels.png" style="width:auto; height:150px;">
        <span class="popuptext smaller40">Actuatoren zorgen ervoor dat de robot zich kan bewegen. Dit zijn bijvoorbeeld de wielen van een robot.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">actuatoren</div>

    </div>

    </body>
    </html>



**Robot tekenspel**
--------------------
    
.. container:: flex-container

   .. container:: half smaller50
    
        **Hoe werkt het?**
        
        #. Gooi de dobbelsteen
        #. Het getal wat je gooit hoort bij een specifiek onderdeel van de robot - Gooi je 6? Dan mag je het onderdeel zelf ontwerpen
        #. Teken dit onderdeel op het tekenvel
        #. Herhaal dit voor elke categorie van de robot
        #. Vergeet de robot niet in te kleuren!

   .. container:: half smaller50

        **Wat heb je nodig?**

        - Het werkblad voor deze opdracht (download deze `hier <_static/media/mirte-lite/mirte-lite-les1/Robot-tekenspel.pdf>`_)
        - Een dobbelsteen
        - Kleurpotloden en/of stiften

        .. image:: _static/media/mirte-lite/mirte-lite-les1/Robots.png
           :width: 450px


**Soorten robots**
--------------------

.. raw:: html

    <!DOCTYPE html>
    <html>
    <head>
    <style>

    .column {
    flex: 1;
    padding: 10px;
    }

    .row {
    display: flex;
    justify-content: center;
    }
    </style>
    </head>
    <body>

    <div class="row">
    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/Industriele-robot.jpg" style="width:auto; height:170px;">
        <span class="popuptext smaller40">Deze robot kan bijvoorbeeld spullen oppakken en verplaatsen naar een andere loopband in de fabriek.</span>
        </div>
    <div style="clear: both;"></div>
    
    <div class="smaller50">industriëel</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/Medische-robot.jpeg" style="width:auto; height:170px;">
        <span class="popuptext smaller40">Medische robots kunnen bijvoorbeeld helpen bij een operatie.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">zorg/medisch</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/Huishoud-robot.jpg" style="width:auto; height:170px;">
        <span class="popuptext smaller40">Deze robots bieden ondersteuning in en rondom het huis, zoals door het gras te maaien.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">huishoud/service</div>

    </div>

    </body>

    <head>
    <style>

    .column {
    flex: 1;
    padding: 10px;
    }

    .row {
    display: flex;
    justify-content: center;
    }
    </style>
    </head>
    <body>

    <div class="row">
    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/Onderwijs-robot.jpg" style="width:auto; height:170px;">
        <span class="popuptext smaller40">Deze robots zijn bedoeld om jou meer te leren over robotica, net zoals de MIRTE robot.</span>
        </div>
    <div style="clear: both;"></div>
    
    <div class="smaller50">onderwijs</div>

    </div>

    <div class="column">
    <div class="popup">
        <img src="_static/media/mirte-lite/mirte-lite-les1/Agrarische-robot.png" style="width:auto; height:170px;">
        <span class="popuptext smaller40">Deze robots helpen mee op het land, door bijvoorbeeld de gewassen water te geven.</span>
        </div>
    <div style="clear: both;"></div>

    <div class="smaller50">agrarisch</div>

    </div>

    </body>
    </html>


**DelFly Nimble - TU Delft**
--------------------
.. container:: smaller70
   
   Een vliegende robot van de TU Delft

.. container:: flex-container
   
   .. container:: half

      .. image:: _static/media/mirte-lite/mirte-lite-les1/DelFly-Nimble-hangend.jpg
         :width: 450px


   .. container:: half smaller50

        Bekijk de video in de volgende slide en beantwoord deze twee vragen:

        #. Waarom is de DelFly Nimble een robot?
        #. Welke onderdelen heeft de DelFly Nimble?


**DelFly Nimble - TU Delft** 
--------------------
.. raw:: html

   <iframe src="https://player.ntr.nl/index.php?id=WO_NTR_16906653" width="600" height="338" frameborder="0" allow="encrypted-media; geolocation" allowfullscreen=""></iframe>


**Waarom is de DelFly Nimble een robot?**
--------------------

.. container:: smaller70
  
   Er zijn 2 antwoorden goed.


   .. raw:: html

      <div class="grid-container">
        <button class="button1">A. het is programmeerbaar</button>
        <button class="button2">B. het kan vliegen</button>
        <button class="button2">C. het kan praten</button>
        <button class="button1">D. het kan reageren op zijn omgeving</button>
      </div>

**Welke onderdelen heeft de DelFly Nimble?**
--------------------

.. container:: smaller70
   
   Er zijn vijf antwoorden goed.

.. raw:: html

   <div class="grid-container4">
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/battery-pack.png"; style="width:auto; height:100px">
        <div>krachtbron</div></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/motor.png"; style="width:auto; height:100px">
        <div>motor</div></button>
        <button class="button4"><img src="_static/media/mirte-lite/mirte-lite-les1/digital-display.png"; style="width:auto; height:100px">
        <div>scherm</div></button>
        <button class="button4"><img src="_static/media/mirte-lite/mirte-lite-les1/controller.png"; style="width:auto; height:100px">
        <div>controller</div></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/nimble-frame.png"; style="width:auto; height:100px">
        <div>frame</div></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/obstacle-sensor.png"; style="width:auto; height:100px">
        <div>sensor</div></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/motor-driver.png"; style="width:auto; height:100px">
        <div>motor driver</div></button>
   </div>

**Zwermrobots - TU Delft**
--------------------

.. container:: flex-container
   
   .. container:: half

      .. image:: _static/media/mirte-lite/mirte-lite-les1/zwermrobots.jpg
         :width: 450px


   .. container:: half smaller50

        Bekijk de video in de volgende slide en beantwoord deze twee vragen:

        #. Waar kunnen de zwermrobots voor gebruikt worden?
        #. Op welke beestjes lijken de zwermrobots?


**Zwermrobots - TU Delft** 
--------------------
.. raw:: html

   <iframe src="https://player.ntr.nl/index.php?id=WO_NTR_16906654" width="600" height="338" frameborder="0" allow="encrypted-media; geolocation" allowfullscreen=""></iframe>


**Waar kunnen de zwermrobots voor gebruikt worden?**
--------------------

.. container:: smaller70
  
   Er is 1 antwoord goed.


   .. raw:: html

      <div class="grid-container">
        <button class="button2">A. gras besproeien</button>
        <button class="button2">B. de weg wijzen</button>
        <button class="button1">C. slachtoffers vinden na een aardbeving</button>
        <button class="button2">D. toezicht houden met een camera</button>
      </div>


**Op welke beestjes lijken de zwermrobots?**
--------------------

.. container:: smaller70
  
   Er zijn 3 antwoorden goed.

.. raw:: html

   <div class="grid-container3">
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/mieren.jpeg"; style="width:auto; height:100px">
        <div>mieren</div></button>
        <button class="button4"><img src="_static/media/mirte-lite/mirte-lite-les1/groene_kikker.jpg"; style="width:auto; height:100px">
        <div>kikkers</div></button>
        <button class="button4"><img src="_static/media/mirte-lite/mirte-lite-les1/spin.jpg"; style="width:auto; height:100px">
        <div>spinnen</div></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/fruitvliegjes.jpg"; style="width:auto; height:100px">
        <div>fruitvliegjes</div></button>
        <button class="button3"><img src="_static/media/mirte-lite/mirte-lite-les1/zwermvogels.jpg"; style="width:auto; height:100px">
        <div>zwermvogels</div></button>
   </div>

**Wat denk jij?**
--------------------

.. revealjs-section::
   :data-background-image: _static/media/mirte-lite/mirte-lite-les1/swirl.png

.. container:: smaller70
  
   Geef jouw mening op de stellingen in de volgende slides.



**Lijken robots meer op mensen of op dieren?**
--------------------

**Mogen robots fouten maken?**
--------------------

**Zou je vrienden kunnen worden met een robot?**
--------------------

**Volgende stap**
--------------------

.. revealjs-section::
   :data-background-image: _static/media/mirte-lite/mirte-lite-les1/MIRTE-end-of-line.png

.. container:: smaller70
  
   Goed gedaan! Je hebt de eerste les afgerond. Nu kun je door naar les 2.




