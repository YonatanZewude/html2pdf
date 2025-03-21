
# PDF Generator med HTML och JavaScript

Denna applikation genererar en PDF-fil från innehållet i ett HTML-element med hjälp av biblioteket `html2pdf.js`. 
Den är designad för att konvertera innehållet i `#wrapper`-elementet till en PDF-fil när användaren klickar på knappen "Generera PDF".


## Funktioner
1. Generera PDF: Konverterar innehållet i `#wrapper` till en PDF-fil.
3. Textfärgjustering: Ändrar textfärgen till svart om den är vit för att säkerställa att texten är synlig i PDF-filen.
4. Hög kvalitet: Använder en högre `scale`-inställning för att minska pixelering i PDF-filen.
5. Döljer knappar: Döljer tillfälligt delningsknappar under PDF-genereringen.

## Teknologier
HTML: För att strukturera innehållet.
CSS: För att styla innehållet.
JavaScript: För att hantera PDF-genereringen.
html2pdf.js: Ett bibliotek som kombinerar `html2canvas` och `jsPDF` för att skapa PDF-filer.
