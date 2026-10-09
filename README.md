# nathalie-bjorkman-u01

Detta är min första portfolio, skapad som en del av
Fullstackutbildningen med JavaScript på Chas Academy.

## Publicerad sida

[Besök min portfolio](https://nathalie-bjorkman.github.io/nathalie-bjorkman-u01/)

## Tekniker

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- Git och GitHub

## Reflektion

### Från skiss till kod

Jag började med att kolla på skissen och kollade då hur de olika sidorna såg ut med layouten, vart man kunde använda Flex och vart Grid skulle kunna vara bättre. Sedan började jag med HTML koden, strukturerade upp den så att den blev semantisk. Så att jag hade `header`, `nav`, `articles`, `sections` och `footer`.

Det som var svårt att översätta till kod med skissen, var font-size och font-weight i mobilversionen, i med att det inte gick att trycka på de delarna i mobilskissen. Men jag försökte lösa detta genom att bara jämföra font-size och font-weight i desktop och mobil. 

### Semantik

Jag använde `header` för sidans sidhuvud och `nav` för navigeringen mellan de olika sidorna. Använde `section` för att dela upp innehållet i olika delar och `article` för innehåll som kan stå för sig självt. Anledningen till att jag valde dessa element var för att de beskriver vad innehållet har för funktion och gör HTML-strukturen lättare att förstå, både för mig som skrivit koden, och för andra.
 
Jag valde 1 `h1` per sida, i med att det är en bra huvudregel att ha en `h1` per sida, sedan `h2`, `h3` i den ordningen, sedan `ul`, `li` och `p`. 
Sedan använde jag mig också utav `a` och `img`. 
Jag använde mig av några `div` för att det då gick att använda i CSS bättre, då kunde `div` användas separat från de andra, i med att det som är innanför `div` är i en "container". `div` har ingen egen semantisk betydelse, så därför passar den som en container när man behöver gruppera elementen för layoutens skull.

Enda stället jag inte använda `div` var i contact delen, där är det endast `section` och vanliga element.

### Layout och responsivitet

Jag använde mig utav Flexbox i `body` på base.css. Och index.html och contact.html blev bara Flexbox, i både mobil och desktop. Det som avgjorde valet, var att Flexbox var lättare att få layouten att bli rätt. 

Jag skrev över i styles.css på några `class` i about.html och technologies.html, där det blev Grid i stället. Och det som avgjorde det valet var att Grid gjorde det lättare att få till layouten med rätt mellanrum. 

I projects.html valde jag Grid till projektkorten eftersom jag ville placera de i både kolumner och rader. Flexbox använde jag då inuti korten eftersom det var lättare att styra hur innehållet skulle fördelas längs en axel. 

Jag gjorde sidan responsiv men hjälp av Grid, Flexbox för mobil och media querys för desktop. Sedan användes även `width: 100%` och `max-width` för att begränsa innehållets bredd, så att sidan kunde anpassas till olika skärmstorlekar utan att innehållet blev för brett.

Jag använde mig också utav CSS boxmodellen, med bland annat margin och padding, för att justera mellanrummen mellan elementen och få layouten att likna Figma-skissen.

Jag lade brytpunkten på 1010px i desktop, för att jag tyckte att det var där det började se lite fult ut, men med en media query till med tablet, så hade det kunnat bli ännu bättre. 

### Tillgänglighet

Det jag har gjort för att sidan ska fungera för fler är att jag har använt beskrivande alt-texter på bilder som inte är dekorativa, så att även personer som använder skärmläsare kan få information om bildernas innehåll. Sedan i med att min html är semantisk, så går det att "tabba" sig igenom länkar och trycka på enter och då kommer man till den sidan utan att behöva använda datormusen. Det har jag testat på alla mina sidor och det funkar. 

Jag testade också min sida med WAVE (Web Accessibility Evaluation Tool). Vid första testet fick jag några kontrast fel och varningar, bland annat för att till exempel footer texten var för ljus i förhållande till bakgrunden och för liten. Jag gick därför tillbaka till CSS-koden och justerade det som behövdes. När jag testade sidan igen visade WAVE inga errors eller alerts. 

Det som återstår är om jag i framtiden lägger till ett formulär på kontaktsidan, så behöver jag även se till så att formulärfälten har kopplade labels och går att använda med tangentbordet. 

### Styrkor och brister

Jag tycker att min sida blev bra över lag för att vara den första sidan jag har byggt helt från grunden. Det jag tycker blev extra bra är själva responsiviteten med home, project och contact sidorna, tycker att de sidorna blev finast. Men det jag skulle bygga om, om jag hade mer tid, är lite på about.html, så att texten employment-type hamnar bättre.

Sedan skulle jag också ändra i technoloiges.html, skulle vilja att techloggorna hamnar lite mer i linje med hamburgermenyn och 007 loggan. 

Skulle också vilja lägga till en tablet media query till i alla fall project.html, där jag skulle använda Grid för att få till två kolumner och tre rader istället, tror att det skulle se finare ut då. 

### AI-verktyg

Jag använde mig utav ChatGPT till hjälp, om jag inte lyckades få till layouten på sättet jag ville, så frågade jag AI, men jag granskade alltid koden och kollade så att det blev bra och kopierade inte rakt av, utan skrev själv och ändrade mycket med margin t.ex. som AI skrev. 

### Versionshantering

Jag använde mig utav Git för versionshanteringen, gjorde en hel del commits och pushar med meddelanden, så att jag lätt kunde gå tillbaka och se vad jag gjorde för ändringar. 



    
