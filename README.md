# API Bootcamp

## Övning 1:

1. Hämta alla pokemons genom en fetch mot API'et

```
https://santosnr6.github.io/Data/pokemons.json
```

2. Rendera ut objekten en och en ut i konsollen

3. Rendera ut objektens namn i DOM'en istället så de blir synliga för en användare

## Övning 2:

1. Hämta alla hundar genom en fetch mot API'et

```
https://santosnr6.github.io/Data/dogs.json
```

2. Rendera ut NAMNEN en och en ut i konsollen

3. Rendera ut dem i DOM'en istället så de blir synliga för en användare

## Övning 3:

1. Hämta alla böcker genom en fetch mot API'et

```
https://santosnr6.github.io/Data/books.json
```

2. Rendera ut de böcker vars sidor inte är längre än 500 pages

## Övning 4:

1. Hämta alla besökare till ett jobb-event genom en fetch mot API'et

```
https://santosnr6.github.io/Data/attendees.json
```

2. Rendera enbart ut de som skall komma

```
attending: true
```

3. Rendera enbart ut de som skall komma OCH som har allergier

## Övning 5:

1. Hämta alla pokemons genom en fetch mot API'et

```
https://santosnr6.github.io/Data/pokemons2.json
```

2. Skapa ett formulär där användaren kan söka efter namnet på en pokemon.

3. Leta reda på den pokemon som användaren sökt efter och gör ett nytt API-anrop på den pokemonens egen URL som finns med i svaren från det första anropet.

4. Presentera data om eftersökt pokemon för användaren i DOM:en.

5. **Levelup!** Lägg till en dropdownlista under din sökruta som visar sökresultaten (max 10 st) som just nu matchar värdet i sökrutan.

## Övning 7: (Veckans Code Review-uppgift)

**Krav 1**
Leta reda på valfritt API på nätet och lista ut hur du får tillgång till det. Lista på olika APIer [hittar ni här](https://github.com/public-apis/public-apis) eller längre ner på sidan.
Skapa nu en ytterst liten webbplats med en enkel layout där du på något sätt använder dig av APIet. Kanske gör du endast ett GET-anrop för att hämta all data som renderas ut, eller vill du låta användarens handlingar avgöra vad som hämtas. Det är upp till dig själv.

**Krav 2**
Dela upp din kod i moduler. Till att börja med kan du skapa modulerna api.js (som sköter alla API-anrop), localStorage.js (om du vill leka med localStorage) och domUtils.js (som gör saker med DOMen), men lägg gärna till fler.

Detta behöver inte vara något avancerat du bygger, utan mer en övning för att utmana dig själv inför veckans Code Review, samt inför kommande examinationsuppgift (hint, hint).

**Tips!** Håll det enkelt!

## Lista på populära APIer

- [Open Weather API](https://openweathermap.org/api)
- [Swapi - Star Wars API](https://swapi.dev/)
- [Poke API](https://pokeapi.co/)
- [Chuck Norris Joke API](https://api.chucknorris.io/)
- [Meme Generator API](https://imgflip.com/api)

## Lista över mina APIer

- [Airbean Products](https://santosnr6.github.io/Data/airbeanproducts.json)
- [Books](https://santosnr6.github.io/Data/books.json)
- [Childrens Books](https://santosnr6.github.io/Data/childrens_books.json)
- [Dogs](https://santosnr6.github.io/Data/dogs.json)
- [Pokemons](https://santosnr6.github.io/Data/pokemons.json)
- [Pokemons 2](https://santosnr6.github.io/Data/pokemons2.json)
- [Pokemon Images](https://santosnr6.github.io/Data/pokemonimages.json)
- [Sinus Products](https://santosnr6.github.io/Data/sinus_products.json)
- [Space](https://santosnr6.github.io/Data/space.json)
- Önskar ni ett API med specifikt tema som ni vill leka med, kan ni be mig att lösa detta. Det går jättesnabbt!
