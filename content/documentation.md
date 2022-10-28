---
Title: Documentation
Description: About the website's technique
hidden: true
---

<div class="documentation">
<h2 class="accent-background">Dokumentation</h2>
<h3>Min teknik inför skapandet av webbsidan</h3>
<i class= "left">- Designprinciper och designelement</i>
<p class= "left">
De designprinciper som jag främst har fokuserat på är följande:
</p>

<ul>
<li class= "left">Balans finns på webbsidan då den består av olika gridsystem för att få en jämn struktur på sidan. Balans återfinns även i färgen på sidan då majoriteten av färgerna är hämtade från herobilden.</li>

<li class= "left">Kontrasten hör delvis ihop med balansen eftersom jag anser att de båda principer krävs för att skapa en balans men samtidigt kontrast. Om hela sidan hade varit uppbyggd med samma gridsystem, exempelvis att varje sida består av två kolumner och ser exakt likadana ut hade det i min mening inte varit en balans. Därför har jag valt att införa kontrast så att på en sida är det två kolumner med information med text i ena och en bild i andra. På en annan sida är det endast en kolumn och på den tredje är det flera stycken men trycker man på en av dem förstoras den upp och man hänvisas till en trekolumn-layout. På så sätt bidrar det till kontrast på sidan men även balans då det inte är samma hela tiden. Betoning är även en princip som finns med i färgschemat för att visa det viktigaste som ska belysas. Exempelvis då besökaren trycker på en specifik highlight och hamnar på en sida där huvudtexten är i skarpare färg än länkarna till vänster för att visa vart huvudfokuset ska hamna på.</li>

<li class= "left">Rörelse går att återfinna i effekterna på sidan. Om man hovrar över en länk förstoras eller förminskas den samtidigt som den skiftar färg. Jag har lagt till pil som länk för att visa i vilken riktning användaren kommer när personen trycker på länken. Om användaren hovrar över huvudrubriken dyker en linje upp i höger riktning som betonar ägarens namn. Det finns även linjer på första-sidan för att rama in de olika kolumnerna vilket är en typ av rörelse. </li>

<li class= "left">Mönstret i bakgrundsbilderna gör att sidan en struktur och ett djup. Den är inte bara platt utan har en eller flera linjer i sig (beroende på vilket tema som är aktiverat)</li>
</ul>

<p class= "left">
De designelement som finns med på sidan går hand i hand med principerna ovan och är följande: </p>

<ul>
<li class= "left">Linjer finns på första-sidan för att markera kolumnerna och skapa en ram-effekt på bilden. Den effekten är även ett form-element som skapar illusionen av en kvadrat eftersom linjerna går ihop.</li>

<li class= "left">Som nämns ovan finns det textur på sidan genom mönstret i bakgrundsbilden som gör att sidan inte känns helt platt.</li>
</ul>

<i class= "left"> - Färg</i>
<p class= "left">
I mitt ljusare tema använder har jag försökt använda mig av en nyanserad färgskala med accentfärgen till grund. För att få ett sammanhang på webbsidan har jag hämtat majoriteten av färgerna från herobilden. Den mer orangea färgen är från skinnsoffan och används som accentfärg över hela sidan (till exempel i loggan). Den beiga färgen är tagen från en punkt i bakgrunden på herobilden och används som en mer generell färg i navbaren och som underrubrik. </p>

<div class= "left">
<table style="text-align: center; border-spacing: 4px; border-collapse: separate; background-color: #E1E1E3;">
<tr>
<td style="height: 50px; width: 50px; background-color: #FAFBFD">
<td style="height: 50px; width: 50px; background-color: #BFB4A5">
<td style="height: 50px; width: 50px; background-color: #C75A2B">
<td style="height: 50px; width: 50px; background-color: #945136">
<td style="height: 50px; width: 50px; background-color: #101010">
</tr>
</table>
</div>

<i class= "left"> - Typografi</i>
<p class= "left">
Jag använder olika typsnitt beroende på vilket tema som är aktiverat. I det ljusa temat använder jag ett typsnitt i sans-serif till mina rubriker och ett typsnitt serif till min brödtext. Varför jag har valt att göra på detta sätt är för att få användaren förstå ännu tydligare vad som är rubriker och få dem att läsa de först. För att göra texten lättläslig har jag gjort variabler som är proportionerliga och används till hela sidans typografi till dess "main font size", "main line height" och "main letter spacing". Det blir proportionerligt då storleken och höjden multipliceras med varandra och skapar en variabel "magic number" som går att använda på hela sidan.
</p>

<i class= "left"> - Känsla</i>
<p class= "left">
Jag vill att känslan som väcks med denna webbplats är nyfikenhet. Genom att uppnå denna känsla har jag försökt göra så den matchar syftet med vad sidan är till för. Eftersom webbplatsen är skapad för att promota en egenföretagare som är "web developer" är det viktigt att kunderna som besöker sidan ser att den är proffsig och skapar en vilja att navigera vidare på sidan och slutligen anlita Bew Gorp till att exempelvis designa deras webbsida.
</p>

<i class= "left"> - SASS</i>
<p class= "left">
Min SASS-kod är strukturerad med hjälp av variabler för att få en enhetlighet med samma färg-schema och typografi m.m. på hela webbplatsen. Jag har olika variabler beroende på vilket tema som är aktiverat och därav två olika stilar som importeras. Mina SASS-filer är uppdelade beroende på vilken del på sidan den tillhör för att lätt kunna navigera och ändra specifik sak på sidan. Till exempel har jag en SASS-fil för typografi, en för footer och en för navbaren osv. 
</p>

<i class= "left"> - Alternativt tema</i>
<p class= "left">I mitt mörka tema har jag ett monokromt färgschema med en accentfärg åt det gröna hållet. Min motivering till varför jag valde färger i gråskala är för att det ska fungera som mörkt läge och ge ett behagligt ljus för att inte överanstränga ögonen och även spara energi på datorn. Den gröna färgen tyckte jag fungerade bra som betoning för att belysa det som är viktigt på sidan och ska fokuseras på (länkar, rubriker, hover-effekter osv.)</p>

<p class= "left">Gridsystemet skiljer sig i det mörka temat från hur det ser ut när det vanliga är aktiverat. På startsidan består den av tre kolumner medan i det ljusa bara av två. Det är även ändringar av gridsystemet på about-sidan och highlight-sidan då about-sidan består av en annan bild och endast en kolumn med flera rader. På highlightsidan består den av två rader med tre kolumner medan i det vanliga bara av en rad med sex kolumner. Ytterligare en ändring är att om man hovrar över navbaren eller länkarna i footern i det mörka temat förminskas länkarna, medan de förstoras i det ljusa temat.</p>

<table style="text-align: center; border-spacing: 4px; border-collapse: separate;background-color: #E1E1E3;">
<tr>
<td style="height: 50px; width: 50px; background-color: #ededed;">
<td style="height: 50px; width: 50px; background-color: #555656">
<td style="height: 50px; width: 50px; background-color: #242424">
<td style="height: 50px; width: 50px; background-color: #0F121A">
<td style="height: 50px; width: 50px; background-color: #00A472;">
</tr>
</table>

<p class= "left">Till mitt mörka tema använder jag enbart typsnitt i sans-serif. Dock är det olika typsnitt där även endast rubrikerna står i versaler och i fetare format. På så sätt är det även här enkelt att se kontrasterna mellan de olika typsnitten.</p>

<p class= "left">Som designprincip i det mörka temat har jag valt att fokusera mer på betoning än i mitt ljusa tema. Eftersom hela sidan är i gråskala ansåg jag, som tidigare nämnt, att en grön färg passade bra för att betona det mest väsentliga på sidan. På startsidan har jag exempelvis ramat in kolumnerna i grön ram och på vissa rubriker har jag lagt till den gröna färgern som bakgrundsfärg. Det finns även en transparens i herobilden för att få fram mönstret i bakgrundsbilden och därav även texturen som designelement för att förstärka djupet på sidan.</p>

<p class= "left">Ytterligare ett designelement är ljusstyrkan på sidan. När det ljusa temat är aktiverat är ljusstyrkan i det "normala" medan om det mörka temat är aktiverat finns det ett filter över hela sidan som gör att ljusstyrkan dämpas en aning och blir mer behagligt för ögonen om besökaren sitter i en mörk omgivning.</p>

</div>
