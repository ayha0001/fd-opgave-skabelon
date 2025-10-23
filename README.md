# Refleksion

Refleksion af opgave

## Læring og process

Denne opgave har været en helt ny måde at arbejde på. Det er ikke noget, vi har prøvet før. I hvert fald ikke at skulle implementere noget, vi har fået udleveret, på denne måde.
Jeg synes generelt, at opgaven har været spændende, og det har været fedt at prøve at arbejde på en ny måde.
Jeg har især lært at gøre mere brug af globale variabler og at definere elementer som f.eks. knapper som globale variabler, som jeg derefter kan bruge flere steder i koden. Det har jeg ikke gjort før - i hvert fald ikke i så stor grad.

## Eksempel på kode

I dette eksempel har jeg arbejdet med at definere tema farver ved hjælp af data-attributter og css variabler. Dette er noget jeg først har lært om i dette semester, og som jeg kun har brugt i små opgaver vi har lavet i skolen. Så det har været fedt at prøve det i en større opgave, og se det fungere.
Ved at bruge dette, har jeg kunne skifte mellem forskellige farvetemaer (primary og secondary) på samme komponent, som skulle bruges flere steder.

Det har været en god måde at kunne sikre ensarthed i designet, da jeg bruger det samme komponent, med præcis samme styling, men så har kunne ændre farven gennem attributterne.

[data-surface="primary"] {
--bg-section: var(--primary03);
--bg-card: var(--secondary01);
--text-section: var(--secondary02);
--card-text: var(--primary03);

/_ knapfarver _/
--btn-bg: var(--secondary02); /_ hvid baggrund _/
--btn-fg: var(--primary03); /_ sort tekst _/

--btn-hover-bg: var(--primary03); /_ sort _/
--btn-hover-fg: var(--secondary02); /_ hvid _/
}

[data-surface="secondary"] {
--bg-section: var(--secondary01);
--bg-card: var(--secondary02);
--text-section: var(--primary03);
--card-text: var(--secondary01);

/_ knapfarver _/
--btn-bg: var(--primary03); /_ sort baggrund _/
--btn-fg: var(--secondary02); /_ hvid tekst _/

--btn-hover-bg: var(--secondary02); /_ hvid _/
--btn-hover-fg: var(--primary03); /_ sort _/
}

## Udfordringer

Selvom jeg synes, at opgaven i sig selv var utrolig spændende og lærerig, føler jeg stadig, at den var meget stor og svær. Især i forhold til den tid, vi havde til rådighed. Jeg kunne godt have ønsket, at vi enten skulle have lavet et par sider mindre, eller at vi havde fået lidt mere tid til at arbejde med opgaven.
Jeg har også gjort brug af tidligere opgaver og koder, som allerede lå i CodePen, hvilket har været en stor hjælp. Dog kan det nogle gange føles, som om man kopierer noget, man måske ikke helt forstår. Jeg har dog forsøgt at sætte mig ind i alt det, jeg har taget fra CodePen, og jeg mener bestemt, at jeg alligevel har lært rigtig meget gennem arbejdet med opgaven.

## Færdige produkt

Jeg nåede desværre ikke helt i mål med opgaven, da jeg ikke fik lavet alle sider. Jeg kom dog frem til, at det var vigtigere for mig at tage mig tid med det, jeg lavede, og gøre det ordentligt, fremfor at haste igennem alt for at blive færdig.
Der er helt klart ting, der kunne forbedres på mit site, og jeg har også måtte skynde mig lidt til sidst for at nå så langt som muligt. Hvis jeg havde haft mere tid, ville jeg helt sikkert have finpudset det mere.
Selvom jeg ikke blev helt færdig, har jeg alligevel lært en masse, som jeg kan tage med mig videre til kommende forløb og til eksamen.
