# Huvudstadens Flytt – hemsida

Statisk webbplats för **Huvudstadens Flytt**, flyttjänster för företag, kontor och hantverkare i Storstockholm: flytt, tunga lyft, magasinering och bortforsling. Varumärket är en del av Avfallskonsulten i Huvudstaden AB.

## Upplägg
- En enda sida: `index.html`, med all CSS och JS inbyggd. Typsnittet Archivo laddas från Google Fonts.
- Sajten ska hostas på **GitHub Pages**, med domänen `huvudstadensflytt.se` (finns i filen `CNAME`). Domänen är registrerad hos Loopia.
- DNS hos Loopia ska ha A-poster för `@` som pekar på 185.199.108.153, .109.153, .110.153 och .111.153, och en CNAME-post för `www` som pekar på `villestrada.github.io`.
- Offertformuläret är en `mailto:`-lösning, utan backend. Om ett riktigt formulär behövs kan Formspree eller Web3Forms användas.

## Kvar att göra
- Telefon 08-684 278 88, offertadress boka@huvudstadensflytt.se och org.nr 559128-0374 är ifyllda (2026-10-16).
- Repo: https://github.com/VilleStrada/huvudstadensflytt (publikt), Pages aktiverat på `main` från roten 2026-10-16. Pusha till `main` så publiceras ändringen.
- DNS hos Loopia pekar ännu på Loopias parkeringsadresser (194.9.94.85/86). Byt till GitHubs A-poster och CNAME för `www` till `villestrada.github.io` (se ovan).
- Bocka i "Enforce HTTPS" när GitHub har godkänt domänen.

## Designprinciper
- Färger: asfalt #22272C, betong #E8EAE8, spännbandsgul #F5B800 (den enda accentfärgen), flyttfiltsblå #2E4877.
- Texterna är på svenska och riktar sig till företag ("ni"). Sajten ska inte tilltala privatkunder.
- Undvik ordet "avfall" i varumärket. Kopplingen till Avfallskonsulten nämns i texten.
