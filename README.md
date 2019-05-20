# Matematik-lommeregner-aarsprojekt

Udarbejdet af Magnus Elfenbein, 2.R slotshaven gymnasium 2019

Jeg har nu arbejdet med Jquery, html og css for at lave en app der skal tage brug i et matematik api. Apiet har forskellige regneoperationer indbygget i sig og formålet er, at lave det om til en funktionel interaktiv lommeregner. Planen er, at man vælger en regne operation i index, ved hjælp af en dropdown menu. Efter kan man så indsætte det uktryk man gerne vil regne på og klikke på en knap, som returnere data fra vores api, som JSON. Denne data vi får skal så sættes pænt op, med eventuelle mellem regninger. 

Api'et jeg bruger har jeg taget herfra: https://newton.now.sh/

Lige nu har jeg min dropdownmenu, mit inputfelt og en knap, som retunere data. Det jeg skal arbejde videre med er, at få dem alle koplet til mit API, så når jeg vælger noget fra dropdown - fx. "Differentier", og skriver mit udtryk ind i input feltet - fx. "x^2", så når jeg klikker på min knap returnere den "2x", fra mit Newton api. Senere vil jeg gerne arbejde mere med CSS på hjemmesiden, få lavet et godt struktureret regneprogram og jeg vil også arbejde hen imod at få integreret, et graphing system, som tegner grafer af mine resultater. Hvis det er muligt vil jeg lave animationer, af graferne herunder fx. når der findes tangenten af et punkt på en graf, så ville det være muligt at få tangenten til at bevæge sig rundt på grafen i en gif, hvor man hele tiden kunne, se værdien ændre sig.

Github pages link: https://melf12.github.io/aarsprojekt-mat-lommeregner/

Til at udvikle denne lommeregner programmere jeg i html, samt javascript og benytter mig af Materialize, JQUERY, Css og Handlebars.js.

Update 14-04:
Koden fungere nu optimalt i forhold til de fundamentale mekaniker lommeregneren skal bruge. Dvs. det er nu muligt at vælge en operation i dropdown menu, skrive et udtryk og få et resultat ud fra api'en. Jeg har kigget og fundet flere graphing bilbioteker, som jeg nu vil arbejde videre på og integrere. Ellers skal jeg også begynde at få gjort det hele pænt med CSS og nogle finde JQUERY animationer. 

Update 20-05-19:
Api'en jeg bruger nemlig https://newton.now.sh/, er umiddelbart gået ned, så programmet vil ikke fungere igennem pages, men koden er der stadig. Venter på følgende information om hvordan jeg skal arbejde videre op til aarsprøven.

Hvis jeg tager op i aarsprøven med dette, tænker jeg, at jeg stadig kan forklare koden og samtidig tegne, hvordan programmet virkede, da at begynde på et nyt projekt er lidt for sent.
