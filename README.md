[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/86U7Ke2S)
Information om denna uppgift [finns på Canvas](https://chasacademy.instructure.com/courses/585/assignments/3056?module_item_id=16220) 


Sammanfattning av projekt
Detta projekt handlade om att skapa en personlig portfolio baserat på en mall som vi fick via figma. I den mallen fanns det 5 "sidor" där 4 st va Obligatoriska och en valfri. 
Fokus var på att göra hemsidan med mobile-first och sedan lägga media queries för att göra hemsidan responsive till fler olika enheter. som telefon --> tablet --> desktop. 
Webbplatsen är byggd med HTML & CSS där fokus låg på struktur, användarvänlighet och korrekt semantisk uppbyggnad av hemsidan. då strukturen av hemsidan redan given så var det bara försöka bygga den enligt mallen. 
Semantiken är viktig för bland annat SEO. CSS användes för att bygga upp designen, typografi och färgschema med hjälp av flexbox och CSS grid. Vilket gjorde det möjligt med en resonsiv layout utan behov av externa ramverk.

Styrkor: Den tydliga designen samt att koden är väl strukturerad och läsbar, användningen av semantiska element som <header> <nav> <section> <main> <footer> bland annat. 
Det förbätterar både tillgängliheten & SEO, responsiviteten fungerar väl på olika enheter utan några konstigheter. 
En till styrka är att man kommer lätt kunna bygga på denna sida genom att lägga till fler länkar funktioner och erfarenheter.

Svagheter: Sidan hade kunnat vara mer interaktiv där man kan använda sig av Javascript för olika funktione. Sen så följer inte sidan fullt ut WCAG-standarder, vilket är något som kan förbättras också. 
Man kan också förbättra och minska CSS filen genom minifiering där Kod som inte behövs för programmets eller websidans funktion tas bort. 

Vad är HTML och dess roll inom frontend?
HyperText Markup Language är grunden i all webbfrontend, det används för strukturera innehållet på en webben.
Exempelvis vart man lägger rubriker, stycken, bilder, länkar osv. HTML definerar sidans innehåll och hirarkin som är avgöranda för både användarna och sökmotorer.
Att skriva semantisk HTML innebär att använda element som tydligt beskriver deras innehåll och funktion. Man använder till exempel <header> för sidhuvud, <nav> för navigation,
<main> för huvudinnehåll och <footer> för sidfot. Detta förättrar WCAG & SEO då strukturen kan tolkas enklare av 
sökmotorer och skärmläsare.

Vad är CSS och dess roll inom frontend?
Cascadinng Style Sheets används för att styra utseende och layout på HTML-element som t.ex. för att definera färger, marginaler, positionering, animationer och typsnitt bland annat. 
CSS separerar strukturen (HTML) från presentation (design), vilket gör att koden lättare att underhålla samt sektionerad. Du kan skriva CSS på flera nivåer (inline, inbäddad, extern) där enligt bäst praxis används den externa stillmallen. Samt används vertyg som CSS grid och flexbox för att skapa flexibla och responsiva layouter utan behov av Javascript tabeller.

Vad menas med responsiv design och hur utvecklar man den?
Responsiv design betyder att webbplatsen ska automatiskt anpassa sig till olika skärmstorlekar på oilka enheter.
Allt från mobil till dator, utan att användaren ska behöva zomma eller scrolla horisontellt.
Metoderna är t.ex.  @media (max/minwidth) när man kan lägga till flera olika brytpunkter.
Sen finns flexbox för flexibla, fler och enradiga layouter. I vissa fall tillsammans med CSS Grid som kan hjälpa med att
skapa mer komplexa tvådiminsionella layouter. Använding av viewport-enheter (vh/vw) för att skapa skalbara element.
Samt användning av mobile-first design, där designen utgår ifrån mobil och sen byggs ut för större skärmar.

WCAG - konkreta tekniker för förbättrad webbplats tillgänglighet
Några centrala tekniker är Alt-texter för bilder så att de kan beskrivas av skärmläsaren.
Tillräcklig färgkontrast mellan text och bakgrund. Så att personer med nedsatt syn/färgblindhet
inte har för svårt att läsa texterna på sidan. Tangentbordsnavigering = alla funktioner ska kunna
nås utan mus. Sematisk HTML och ARIA-roller(role="navigation") för att underlätta tolkningen.
Undivk alltför blinkande och röriga element så att sidan inte orsakar några epileptiska anfall.

Viktigaste UX/UI principer inom frontend
Att vara konsekvent med typsnitt, färg, och knappar över hela sidan. Tydlig hirarki där du styr det visuella genom storlek, färg och kontrast. Feedback i form av hover eller klickbara effekter, de låter dig veta när du interagerar med något element. Hålla saker simpla så att du inte stör 
användarens mål. Responsiv och balanserad design. gränssnitten ska kännas naturlig på alla enheter
