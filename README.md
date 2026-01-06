# Första hemsidan – ett guidat mall-repo

**Välkommen!** 👋  
Detta repo är en mall och ett kursmaterial för dig som vill lära dig att bygga din **första egna hemsida** gratis med **GitHub Pages**.

I de första lektionerna kommer du steg för steg att bygga en enkel hemsida med **HTML, CSS och enkel JavaScript**. Senare går kursen vidare med lektioner som gör den till en webbapp, introducerar ramverket **Svelte**, och slutligen hur **AI** kan användas som verktyg i arbetet.

Allt sker:
- i webbläsaren
- via GitHub
- utan installation
- utan krav på egen dator (surfplatta fungerar också)

Detta kan vara första gången du använder GitHub. Det är helt okej.  
Du kommer här att lära dig både att skapa en hemsida från grunden och hur man sparar varje steg, så att det går att gå tillbaka om något inte blev som du tänkt dig.

---

## VIKTIGT: Om att lära sig mer (och inte kunna allt)

Det här materialet är inte tänkt att lära dig **allt** om webbutveckling.  
Målet är att du ska **komma igång**, förstå grunderna och känna dig trygg med hur saker hänger ihop.

När du vill göra något som inte står med här är det helt normalt att:
- söka information själv
- läsa dokumentation
- prova dig fram

Det finns mycket bra hjälp att hitta.  
En klassisk och lättillgänglig resurs är till exempel:
- https://www.w3schools.com
En annan:
- https://developer.mozilla.org/en-US/

Du kan också:
- söka med Google eller annan sökmotor
- ställa frågor till AI-tjänster, om du använder sådana

Men tänk på detta:
- använd AI som **stöd**, inte som ersättning för att förstå
- låt inte någon annan (eller något annat) göra jobbet åt dig utan att du vet vad som händer

Hela poängen med kursen är att:
- förstå grunderna
- lära sig koncepten
- kunna bygga vidare själv

Det är helt okej att inte kunna allt.  
Det viktiga är att du vet **hur du tar reda på mer**.

---

## Innan du börjar – GitHub-konto

För att kunna delta behöver du ett **gratis GitHub-konto**.

### Skapa konto
1. Gå till sidan för att skapa ett konto: https://github.com/signup  
   (<a href="https://github.com/signup" target="_blank" rel="noopener noreferrer">Öppna i nytt fönster/tab</a>)
2. Fyll i:
   - e-postadress
   - lösenord
   - användarnamn
3. Följ stegen tills kontot är skapat
4. Kom tillbaka hit och **uppdatera sidan** 🔄

👉 Det kostar ingenting.

---

### Logga in
Om du redan har ett konto:
1. Gå till sidan för inloggning: https://github.com/login  
   (<a href="https://github.com/login" target="_blank" rel="noopener noreferrer">Öppna i nytt fönster/tab</a>)
2. Logga in med ditt användarnamn och lösenord
3. Kom tillbaka hit och **uppdatera sidan** 🔄

När du är inloggad kan du börja kursen.

---

## Kom igång med kursen

### Skapa ditt eget repo (din arbetsyta)

Högst upp på sidan finns en knapp som heter **Use this template**.

1. Klicka på **Use this template**
2. Välj **Create a new repository**
3. Ge ditt repo ett namn (t.ex. `min-forsta-hemsida`)
4. Klicka **Create repository**

Nu har du skapat **din egen kopia** av kursmaterialet.

Det är i *din* kopia du kommer att arbeta.  
Du ändrar ingenting i kursens original.

---

## Slå på GitHub Pages (publicera din sida)

För att din hemsida ska synas på webben behöver **GitHub Pages** vara aktiverat.

Gör så här i *ditt* repo:

1. Klicka på **Settings**
2. Klicka på **Pages** i menyn till vänster
3. Under **Source**, välj:
   - **GitHub Actions**
4. Klart – inställningen sparas automatiskt

När detta är gjort publiceras din hemsida automatiskt när du sparar ändringar.

---

## Se din hemsida på webben (URL)

När GitHub Pages är påslaget får din hemsida en egen webbadress.

### Din adress (URL) ser ut så här:
https://DITT-GITHUB-NAMN.github.io/DITT-REPO-NAMN/

### Exempel
- GitHub-namn: `anna123`
- Repo-namn: `min-forsta-hemsida`

➡️ Adressen blir:
https://anna123.github.io/min-forsta-hemsida/

### Hitta länken i GitHub (säkraste sättet)
1. Gå till **Settings**
2. Klicka på **Pages**
3. Där visas en klickbar länk:  
   *“Your site is live at …”*

### Om du inte ser ändringen direkt
- Vänta några sekunder (ibland upp till 1 minut)
- Uppdatera webbsidan i webbläsaren 🔄  

---

## Hur vi jobbar i kursen

- Du jobbar alltid i webbläsaren
- Du behöver inte ladda ner något
- Du behöver inte använda terminal eller kommandon

### Viktiga begrepp (kort förklaring)
- **Repo** = din projektmapp på GitHub
- **Fil** = t.ex. `index.html`
- **Commit** = spara en ändring
- **Branch** = ett steg i kursen
- **Merge** = lägga till nästa steg i ditt repo

Du behöver inte kunna detta i förväg.  
Du lär dig genom att göra.

---

## Lesson 1 – Min första hemsida

Lesson 1 handlar om att bygga en **statisk hemsida** som fungerar på:
- mobil
- surfplatta
- dator

Du kommer steg för steg att:
- ändra text
- skapa fler sidor
- använda listor och tabeller
- lägga in bilder och länkar
- bygga en meny
- göra menyn interaktiv med JavaScript
- ändra färger och typsnitt med CSS
- testa sidan i olika skärmstorlekar

När Lesson 1 är klar har du en **färdig personlig hemsida**.

---

## Lesson 1.0 – Start

I detta första steg finns:
- en fil: `index.html`
- ingen CSS
- ingen JavaScript

Det är medvetet enkelt.

### Uppgift
1. Klicka på filen `index.html`
2. Klicka på penn-ikonen (Edit)
3. Ändra texten i rubriken
4. Klicka **Commit changes**

Efter några sekunder uppdateras sidan automatiskt.  
Om ändringen inte syns direkt: uppdatera webbsidan 🔄

Du har nu publicerat din första hemsida.

---

## Hur du går vidare till nästa lektion

När det är dags att gå vidare till nästa steg gör du så här:

1. Klicka på fliken **Pull requests**
2. Klicka **New pull request**
3. Välj:
   - **base:** `main`
   - **compare:** den lesson-branch som ni går vidare till  
     (t.ex. `lesson-1.1-pages`)
4. Titta på ändringarna som visas
   - grönt = nytt
   - rött = borttaget
5. Klicka **Merge pull request**

Det du har skrivit finns kvar.  
Ny kod och nya filer läggs till.

---

## Om något känns svårt

Det är normalt.

Tips:
- ändra en sak i taget
- spara (*commit*) ofta
- om något inte fungerar:
  - högerklicka på sidan → **Inspektera**
  - öppna fliken **Console**
  - röd text betyder fel, inte att du gjort något “fel”

Fel är information.

---

## Vad som kommer senare

Efter Lesson 1 kommer kursen att fortsätta med:
- innehåll som hämtas från data (JSON)
- JavaScript som bygger sidan automatiskt (DOM)
- listor och tabeller från data
- ändra innehåll direkt på sidan
- spara tillbaka till en datakälla
- webbappar och ramverk (Svelte)
- AI som stöd och verktyg

Allt bygger vidare på det du gör här.

---

## Sammanfattning

Detta repo är:
- din arbetsyta
- ett kursmaterial
- en plats att prova och lära

Du bygger steg för steg.  
Du behåller det du skapar.  
Du ser exakt vad som tillkommer.

**Välkommen – nu börjar vi.**
