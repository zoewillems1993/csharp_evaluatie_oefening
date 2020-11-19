# csharp_evaluatie_oefening
Maak deze oefening als huiswerk

using System;

namespace praktijk_oefening1
{
    class Program
    {
        static void Main(string[] args)
        {
            /*
             * Praktijk oefen vragen
             * 
             * Werk alle opdrachten uit in de Main, tenzij er gevraagd wordt
             * om een andere methode te maken
             * 
             */

            /*
             * Opdracht 1
             * Maak een array van tekst met 5 elementen 
             * Loop door elk element van de array heen en toon dit
             * op het scherm
             */

            /*
             * Opdracht 2
             * Maak een array van getallen met 8 elementen
             * Loop door elk element van de array heen en toon dit op het scherm
             * Tel alle getallen bij elkaar op
             * Toon aan het einde in een zin het totaal van alle getallen
             */

            /*
             * Opdracht 3
             * Maak een array van 10 keer de prijs van een artikel met 2 cijfers
             * achter de komma met minimaal 4.25, 9.50, 13.75, 1.75 in de array
             * Loop door elk element van de array heen en toon dit op het scherm
             * Toon aan het einde hoeveel producten goedkoper zijn dan 8.50 en 
             * hoeveel producten er duurder zijn dan 8.49
             */

            /*
             * Opdracht 4
             * Toon een vraag: "Wat is je naam"
             * Sla de naam van de gebruiker op in een variabele
             * Toon daarna een zin: "Welkom .... in deze applicatie"
             * Op de puntjes komt de naam van de gebruiker
             */

            /*
             * Opdracht 5
             * Maak een nieuwe methode GetAge
             * De methode vraagt aan de gebruiker zijn leeftijd
             * Nadat de gebruiker zijn leeftijd heeft ingevoerd toont de 
             *   applicatie een zin met “Jouw leeftijd is….” jaar uiteraard met de 
             *   leeftijd van de gebruiker op de puntjes
             * Zorg dat de vraag/ methode uitgevoerd wordt als het programma gestart wordt
             */

            /*
             * Opdracht 6
             * Ga door met de oplossing uit opdracht 5
             * Gebruik de naam van de gebruiker uit opdracht 5 en toon die 
             * in de methode van GetAge
             * Er komt dus in beeld:
             * “Welkom …. je leeftijd is ….” 
             * Op de puntjes komen de naam en de leeftijd van de gebruiker
             */

            /*
             * Opdracht 7
             * Ga door met de oplossing uit opdracht 6
             * Stuur in de methode de leeftijd terug naar de Main en toon in 
             * de Main dan een zin met de leeftijd en naam van de gebruiker
             */


            /*
             * Opdracht 8
             * Toon in de methode ShowFruitMessage op een zo efficient mogelijke
             * manier de volgende tekst:
             * Bij een Banaan: "Een kromme zoet stukje fruit"
             * Bij een Peer: "Lekkere sappige peer"
             * Bij een Mandarijn: "Heerlijk te pellen oranje vrucht"
             * Bij een Citroen: "Baby's kijken heel zuur van een Citroen"
             * Bij een Aardbei: "Rood omdat hij zich schaamt voor zijn pitjes"
             * Bij een Manderijn: "Neem nog eens wat taal-lessen bij mevrouw Kuijt"
             * In alle andere gevallen: "Dat is vast niet heel gezond....."
             */
            ShowFruitMessage("Banaan");
            ShowFruitMessage("Appel");
            ShowFruitMessage("Peer");
            ShowFruitMessage("Snickers");
            ShowFruitMessage("Mandarijn");
            ShowFruitMessage("Manderijn");
            ShowFruitMessage("Citroen");
            ShowFruitMessage("Aarbei");
            ShowFruitMessage("Mars");

            /*
             * Opdracht 9
             * Schrijf de 9 regels van opdracht 8 (de ShowFruitMessage regels)
             * op een andere wijze dat deze in maximaal 4 regels uitgevoerd 
             * worden
             */
            
        }

        static void ShowFruitMessage(string sortFruit)
        {
            //
        }
    }
}
