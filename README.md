# nathalie-bjorkman-u01

https://nathalie-bjorkman.github.io/nathalie-bjorkman-u01/


- **Från skiss till kod.**

    Jag började med att kolla på skissen och kollade då hur de olika sidorna såg ut med layouten, vart man kunde använda flex och vart grid skulle kunna vara bättre. Sedan började jag med HTML koden, struktuerade upp den så att den blev semantisk. Så att jag hade `header`, `nav`, `articles`, `sections` och `footer`.

    Det som var svårt att översätta till kod med skissen, var font-sise och font-weight i mobilversionen, i med att det inte gick att trycka på de delarna i mobilskissen. Men jag försökte lösa detta genom att bara jämföra font-size och font-weight i desktop och mobil. 

- **Semantik.** 

    Jag valde 1 `h1` per sida, i med att det behövs för att det ska vara hieraki, sedan `h2`, `h3` i den ordningen, sedan `ul`, `li` och `p`. 
    Sedan använde jag mig också utav `a`, `img` och. Jag använde mig av några `div` för att det då gick att använda i CSS bättre, då kunde `div` användas separat från de andra, i med att det som är innanför `div` är i en "container". 

    Enda stället jag inte använda `div` var i contact delen, där är det endast `section` och vanliga element.

- **Layout.** Var använde du Flexbox, var använde du Grid, och vad avgjorde valet? Hur gjorde du sidan responsiv, och varför lade du brytpunkterna där du gjorde?

    Jag använde mig utav Flexbox i `body` på base.css. Och index.html och contact.html blev bara Flexbox, i både mobil och desktop. Det som avgjorde valet, var att Flexbox var lättare att få layouten att bli rätt. 

    Jag skrev över i styles.css på några `class` i about.html och technologies.html, där det blev Grid istället. Och det som avgjorde det valet var att Grid gjorde det lättare att få till layouten med rätt mellanrum. 

    I projects.html blev det både Grid och Flexbox för att själva "lådorna" med informationen, blev bättre med Grid, för att få de 6 "lådorna" att hamna i kolumner och rader. Men Flexbox användes för texten inuti "lådorna", så att länkaran t.ex hamnade med space-between. 

    Jag gjorde sidan responsiv men hjälp av Grid, Flexbox för mobil och media queries för desktop. Sedan användes även width: 100% och max-width: 1200px / 700px för att få sidan att bli responsiv. 

    Jag lade brytpunkten på 1010px i desktop, för att jag tyckte att det var där det började se lite fult ut, men med en media querie till med tablet, så hade det kunnat bli ännu bättre. 

- **Tillgänglighet.** Vad har du gjort för att sidan ska gå att använda för fler? Hur testade du det, och vad visade testet? Vad återstår?

    Det jag har gjort för att sidan ska fungera för fler är att jag har `alt=""` på bilder som inte är dekorativa och det beskriver vad bilden symboliserar. Sedan i med att min html är semantisk, så går det att "tabba" sig igenom länkar och och trycka på enter och då kommer man till den sidan utan att behöva använda datormusen. Det har jag testat på alla mina sidor och det funkar. 

    Jag testade också min sida på denna websida: https://wave.webaim.org/ fick där lite contrast errors och alerts, texten är för liten och för ljus i förhållande till bakgrunden, då det är något som behöver fixas. Men jag tog färgerna och storlekarna från Figma skissen. 

    Det som återstår är om jag kommer lägga till ett input fält i contact.html, då kommer jag behöva testa så att den funkar att skriva i utan att använda datormusen.

- **Styrkor och brister.** Vad blev bra, och vad skulle du bygga om med mer tid?

    Jag tycker att min sida blev bra överlag för att vara den första sidan jag har byggt helt från grunden. Det jag tycker blev extra bra är själva responsiviteten med  home, project och contact sidorna, tycker att de sidorna blev finast. Men det jag skulle bygga om, om jag hade mer tid, är lite på about.html, så att texten employment-type hamnar bättre och texten lite större överlag. 

    Sedan skulle jag också ändra i technoloiges.html, skulle vilja att techloggorna hamnar lite mer i linje med hambugemenyn och 007 loggan. 

    Skulle också vilja lägga till en tablet media query till i alla fall project.html, där jag skulle använda grid för att få till två kolumner och tre rader istället, tror att det skulle se finare ut då. 

- **AI-verktyg.** Om du använt dem: till vad, och vad ändrade du i det som genererades?

    Jag använde mig utav ChatGPT till hjälp, om jag inte lyckades få till layouten på sättet jag ville, så frågade jag AI, men jag granskade alltid koden och kollade så att det blev bra och kopierade inte rakt av, utan skrev själv och ändrade mycket med margin t.ex som AI skrev. 
