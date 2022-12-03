# linalg-2022
Lösningar till rekommenderade uppgifter i kursen SF1624 - Algebra och geometri. De uppgifter som löses här är de som finns i pdferna i `pdfs`.

# Hur får man pdfen?
[Länk till pdfen](https://github.com/simon-rosen/linalg-2022/blob/main/linalg_2022.pdf)


# Om man vill lägga till lösningar
## Hur lägger man till lösningar?
Lägg till lösningar under `modulX/uppgifter_att_borja_med/Y.tex` det finns mallar för hur de bör se ut i `modul1/uppgifter_att_borja_med/mall.tex`

Referera gärna till formler som används i lösningen med `\ref{formalnamn}`. Nya formler för en modul kan läggas till i `modulX/teori.tex`.

## Handskrivna lösningar
Man kan lägga till handskrivna lösningar om man skannar in dom som en pdf och sedan lägger dom i `modulX/uppgifter_att_borja_med/inskannat/<uppgiftnummer>.pdf`.

OBS: pdf:en måste heta `<uppgiftnummer>.pdf`. Exempel: uppgift 1 ska heta `1.pdf`.

Om det finns både en latex-lösning och en handskriven lösning kommer latex-lösningen att prioriteras. Latex-lösningar är att föredra eftersom att de är snyggare och lättare att modifiera, men det går snabbare att skriva lösningar för hand.

### Handskriven teori
Man kan även lägga till handskriven teori

1. Lägg till en inskannad pdf i `modulX/teori_inskannat/namn.pdf`
2. lägg manuellt till `\handskriventeori{<namn>}{teori_inskannat/<namn>.pdf}` i filen `modulX/teori.tex`.

Ex om man vill lägga till en handskriven text om gausseliminering i modul 2: 

1. Lägg till din pdf `gausseliminering.pdf` i mappen `modul2/teori_inskannat`
2. Lägg till raden `\handskriventeori{gausseliminering}{teori_inskannat/gausseliminering.pdf}` i modul2/teori.tex


## Macros för att skriva mindre latex kod
De har jag lagt i `macros.tex`. T.ex finns det ett kommando för att skapa lösningar till deluppgifter, alltså att skriva typ **a)**, som används såhär `\subsolution{deluppgift}`.
