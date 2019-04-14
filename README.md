#Matematik lommeregner projekt:
Titel: måske - "Interaktiv lommeregner"


Jeg har nu arbejdet med Jquery, html og css for at lave en app der skal tage brug i et matematik api. Apiet har forskellige regneoperationer indbygget i sig og formålet er, at lave det om til en funktionel interaktiv lommeregner. Planen er, at man vælger en regne operation i index, ved hjælp af en dropdown menu. Efter kan man så indsætte det uktryk man gerne vil regne på og klikke på en knap, som returnere data fra vores api, som JSON. Denne data vi får skal så sættes pænt op, med eventuelle mellem regninger. 

Api'et jeg bruger har jeg taget herfra: https://newton.now.sh/

Lige nu har jeg min dropdownmenu, mit inputfelt og en knap, som retunere data. Det jeg skal arbejde videre med er, at få dem alle koplet til mit API, så når jeg vælger noget fra dropdown - fx. "Differentier", og skriver mit udtryk ind i input feltet - fx. "x^2", så når jeg klikker på min knap returnere den "2x", fra mit Newton api. Senere vil jeg gerne arbejde mere med CSS på hjemmesiden, få lavet et godt struktureret regneprogram og jeg vil også arbejde hen imod at få integreret, et graphing system, som tegner grafer af mine resultater. Hvis det er muligt vil jeg lave animationer, af graferne herunder fx. når der findes tangenten af et punkt på en graf, så ville det være muligt at få tangenten til at bevæge sig rundt på grafen i en gif, hvor man hele tiden kunne, se værdien ændre sig.

Til at udvikle denne lommeregner programmere jeg i html, samt javascript og benytter mig af Materialize, JQUERY, Css og Handlebars.js.



# api_one_page_template
This is a one-page template to make a neat web-app using an external API with jQuery. The app use the following frameworks and boilerplates:

<ul>
<li><a href="https://github.com/toddmotto/public-apis">Some public API with little or no authentication</a></li>
<li><a href="https://handlebarsjs.com/">Handlebars javascript</a></li>
<li><a href="https://materializecss.com/">Materialize css</a></li>
<li><a href="https://jquery.com/">jQuery</a></li>
</ul>

To get started, download the project and open index.html in your browser as well as in a code editor. Study the structure to get an overall picture of how handlebars, jQuery and Materialize work together to show the results from the API queries. 

Use the template to create your own app with an API of your liking or needs. 
      
