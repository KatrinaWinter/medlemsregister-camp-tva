# medlemsregister-camp-tva

## Ett problem vi löste

I båda feature-grenarna gjorde vi ändringar på samma println-rad i src/Main.java. 
När den ena grenen slogs ihop med main uppstod en konflikt för den andra grenen. 
Vi hämtade därför in ändringarna från main lokalt med Git och gick igenom de delar av koden som markerats som konflikt. 
Därefter enades vi om vilken text som skulle användas och tog bort Git-markeringarna. 
När koden hade kontrollerats med javac lade vi till filen i staging och skapade en commit för att slutföra mergeprocessen.