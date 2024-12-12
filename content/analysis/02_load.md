---
Title: LOAD
Description: This is my color page.
Template: analysis
---

Utvärdering av laddningstid
=======================

Denna uppgiften handlar om att utvärdera laddningstiden
på olika webbsidor.

Urval
-----------------------

Jag valde att undersöka:

<a href="https://sv.wikipedia.org/wiki/Portal:Huvudsida" class="webchoices" >Wikipedia.org</a>

<img class="screenshotimage" src="%base_url%/image/screenshotWikipedia.png" alt="Wikipedia screenshot">


<a href="https://pixabay.com/sv/" class="webchoices" > Pixabay.com </a>

<img class="screenshotimage" src="%base_url%/image/screenshotPixabay.png" alt="Pixabay screenshot">


<a href="https://store.dji.com/se?utm_source=google&utm_medium=cpc&gad_source=1&gclid=CjwKCAiAjeW6BhBAEiwAdKltMnCxzFo3uLm-a3oe0E6QJrw0e8mAj8bK7Cav_oQqJ2LAqrDGWXqZ-hoCJ48QAvD_BwE" class="webchoices" >store.dji.com</a>


<img class="screenshotimage" src="%base_url%/image/screenshotDji.png" alt="DJI screenshot">

Anledningen till att jag valde just dessa sidor var pga följande:

<b> Wikipedia </b> pga av att det är en hemsida som generellt sätt har mycket information vilket lätt kan byggas upp till en hel del data samt att de har många sidor som laddas. Vilket gör det till en bra kandidat till denna rapporten. 

<b> Dji </b> valdes pga att de brukar ha väldigt mycket saker som sker på deras sidor i form av exempelvis bilder som justeras vid scroll men även ibland virtuella modeller av produkter de visar upp som man kan interaktera med. Vilket är saker som oftast brukar ta mer kraft från datorn och därför intressant att kolla på. 

<b> Pixabay </b> valdes utav den anledningen att de har jättemycket bilder och bilder i hög kvalite framförallt. Vilket brukar vara saker som drastiskt saktar ner sidan. Vilket var anledningen jag valde denna. Då jag ville undersöka hur de löst detta då jag ej upplevt att deras sida nödvändigtvis går långsamt. 


Metod
-----------------------

Jag tog hjälp utav en verktyget som heter "Inspektera". När jag öppnade denna så öppnade inspektera fliken valde jag "Network" och därefter laddade jag om sidan. När man var kvar i inspektera läget för att få upp informationen man var uteefter. Därefter så kollade jag på följande delar som fanns längst ner i "Network delen". 

Nämligen: 
"... requests" -> för att få fram laddningstiden

"... resources" -> för att få fram antalet resurser

"load: ..." -> för att få fram sidans totala storlek.

Sedan gjorde jag detta 3 gånger per sida och antecknade värdena jag fick fram i excelbladet som ni även ser här nedan. 


<iframe class="excel" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSAGT_-rrPjhN3SVC04m2Bykg5S3icUsD2TAfrpG8UvGLufm0KPiK2KXds5it7lxj2Fu-KjqHEH42bM/pubhtml?widget=true&amp;headers=false"></iframe>

Resultat
-----------------------

Som ni ser i ovan excel ark så skiljer sig värdena mellan försök ej så drastiskt åt utan håller sig väldigt lika varandra. Däremot ser man om man jämför värdena mellan de olika webbsidorna så skiljer dessa värden sig en hel del åt. Som man ser i tabellen har DJI drastiskt mycket högre laddningstid i snitt än vad de 2 andra sidorna har. Sedan är det Pixabay och sist Wikipedia med lägst laddningstid. 

När det sedan kommer till antalet resurser som laddas så så skiljer dessa även sig åt och även här så är det DJI som har högst värde och de andra följer samma ordning som tidigare. 

Detta "mönstret" fortsätter även in på sidornas totala storlek där DJI har en drastiskt mycket större storlek än de övriga då den laddar värdena i sekunder (s)
istället för millisekunder (ms) som de övriga sidorna gör. 

Analys
-----------------------

Dji som man även såg i resultat delen har absolut störst värden på alla fronter (dvs: laddningstid, antalet resurser och sidans totala storlek). Dock har ju
Dji också väldigt mycket rörliga delar på sin sida med dels animationer men också av och till moduler på deras produkter som man kan se i 3d. Vilket
tar mer plats än bilder som pixabay eller mestadels text som wikipedia har. Vilket gör att värdena vi får är logiska baserat på vad för typ av innehåll de har på sina
sidor. 

Rankning av webbsidorna baserad på deras mätvärden (från lägst till högst): 

- Vinnare: Wikipedia
- Pixabay
- DJI


Varför detta är falet är rätt tydligt och har förklarats ovan. Det som DJI kan göra annorlunda är att kanske se över vad det är på deras sidor som tar så mycket tid att ladda, storlek på webbsidan och utifrån det se om det finns någon åtgärd för detta som gör att både laddningstiden och den totala storleken på sidan minskas. 

Så i det stora hela beror det mycket på vad det är som sidan innehåller hur snabbt laddningstiden mm blir. Som att wikipedia laddar snabbt då det mestadels är text som ska laddas in. Men att det gäller att tänka på vad för element mm man har på sin sida och framförallt finns det något bra sätt att minska att det tar så mycket tid/plats som det gör. Ett enkelt sätt är exempelvis att jobba med bilderna och storleken/Kvaliten på den för att på ett snabbt och smidigt sätt få ner storleken varje bild tar. 

Jag tyckte pixabay hade okej laddningstid (runt 60 i laddningstid) och allt där under är också bra. SÅ skulle nog säga att det är acceptabelt men för att jag skulle klassa det som ordentlig snabb laddningstid får jag nog hellre gå på likt wikipedia som ligger på runt 50 i laddningstid. Utgår man från det så passerar varken Pixabay 
eller DJI detta kravet. Men som sagt detta är också lite olika baserat på innehåll och person till person såklart. 

Referenser
-----------------------

Sidorna som undersöktes webbplatser (som även nämns ovan):


<a href="https://sv.wikipedia.org/wiki/Portal:Huvudsida" class="links">Wikipedia</a> - använd: 2024-12-11 & 2024-12-12 (datan hämtade från datum 2) 

<a href="https://pixabay.com/sv/" class="links">Pixabay</a> - använd: 2024-12-11 & 2024-12-12 (datan hämtade från datum 2) 

<a href="https://store.dji.com/se?utm_source=google&utm_medium=cpc&gad_source=1&gclid=CjwKCAiAjeW6BhBAEiwAdKltMnCxzFo3uLm-a3oe0E6QJrw0e8mAj8bK7Cav_oQqJ2LAqrDGWXqZ-hoCJ48QAvD_BwE" class="links">DJI</a> - använd: 2024-12-11 & 2024-12-12 (datan hämtade från datum 2)

Övrigt
-----------------------

Amélie Jacobsen och denna rapporten skrevs av mig individuellt. 