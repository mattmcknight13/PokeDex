

## Project Name

PokeDex

deployed site :https://mattmcknight13.github.io/PokeDex/

## Project Description

Will allow user to type in a pokemon name from a input field and display a sprites along with basic information about that pokemon.
Will do this by taking the name and fetching information by talking to a third party API.
When user types in a new pokemon it will remove the previous and display the new one.

## API and Data Samplehttps://github.com/mattmcknight13/PokeDex.git

PokeAPI: https://pokeapi.co/docs/v2

Sample JSON:
```json
{
    "abilities": [
        {
            "ability": {
                "name": "torrent",
                "url": "https://pokeapi.co/api/v2/ability/67/"
            },
            "is_hidden": false,
            "slot": 1
        },
        {
            "ability": {
                "name": "rain-dish",
                "url": "https://pokeapi.co/api/v2/ability/44/"
            },
            "is_hidden": true,
            "slot": 3
        }
    ],
    "base_experience": 63,
    "forms": [
        {
            "name": "squirtle",
            "url": "https://pokeapi.co/api/v2/pokemon-form/7/"
        }
```


## Wireframes

Upload images of your wireframes to an image hosting site or add them to an assets folder in your repo and link them here with a description of each specific wireframe.

Desktop:

![wireframe](https://imgur.com/xA8JDh3.png)


Mobile:

![wireframe](https://imgur.com/xz0FJYn.png)


Header: will display name of Project, and my name (should we acknoledge the api we use here?)
ex. PokeDex by Matthew McKnight with help of PokeAPI.

Page:
Big box will be background of app styled to look like a pokedex
input field will be where user types in name of a pokemon
Image will display clearly
and information below it in a oraginzied setting.

#### MVP 


- Allow user to select a pokemon 
- Reach external Api to render height, id, name, weight...
- css styling for background, and display
- add selected pokemon and properties to the DOM to be displayed
- removed from Dom when a new pokemon is selected


#### PostMVP 
- Allow user to select from a list of pokemon instead of a text input in the desktop version
- added decoration css styling (buttons, lights)
- add type attribute as a background change based on pokemon
- animation for sprite to move between back facing view to front facing view when first appears/ or show both sprites at once.
-Add a timer to remove the displayed pokemon after set interval.


## Project Schedule

|  Day | Deliverable | Status
|---|---| ---|
|August 14-16| Prompt / Wireframes / Priority Matrix / Timeframes | Complete
|August 17| Project Approval, core structure start | Complete
|August 18| finish core strutcure, api use and testing ,css mobile | Complete
|August 19| css desktop, MVP, Post MVP's | Complete
|August 20| Post MVP, testing | Complete
|August 21| Presentations | Incomplete

## Priority Matrix

![priority Matrix](https://imgur.com/nyzgGNe.png)

## Timeframes

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| core HTML | M| 3hrs| 3hrs | 3hrs |
| core CSS | M| 3hrs| 2hrs | 2hrs |
| core JS | M| 3hrs| 4hrs | 4hrs |
| Input functionality | H | 3hrs | 2hrs | 2hrs |
| Remove Functionality | M | 3hrs | 1hrs | 1hrs|
| Working with API | H | 3rs| 2hrs | 2hrs |
| CSS Styling screen  | H | 3hrs | 5hrs | 5hrs |
| CSS Styling input bar  | L| 1hrs | 1hrs | 1hrs |
| CSS Styling Text-Box  | L | 1.5hrs | 2hrs | 2hrs |
| CSS Styling background  | M | 3hrs | 2hrs | 2hrs |
| CSS Styling fetch positioning  | H | 3hrs | 3hrs | 3hrs |
| Post MVP JS  | L | 2hrs | 2hrs | 2hrs |
| Testing  | L | 1.5hrs | 1.5hrs | 1.5hrs |
| Total |  | 31hrs| 30hrs | 30hrs |

## Code Snippet

 Takes in the input string and turns everycharacter into a lower case to match up with catoraiztion methods of the API, to allow for spelling to not hinder search.

```
function changeLetter(input) {
  const letter = input
  const name =letter.toLowerCase()
  getPokemon(name)
}
```

## Change Log
 Modifyied css so page felt more dynamic and used.




