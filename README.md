# ConMap
<i>A map of J. Valoch's contacts. Proof of concept made for Moravian Gallery in Brno</i>

## Backstory
A while ago I was asked by a friend of mine (working at Moravian Gallery in Brno) to help with a project of hers. Her job was to gather <b>all correspondence</b> contacts of Jiří Valoch - czech artist. It was about 3000+ people across nearly a thousand cities worldwide. My job was then to try to visualize all the contacts on a world map. 

Using a Python script I wrote (with the help of Nominatim library), I was able to convert all the cities' names - in the table she provided me - to GPS coordinations. These coordinations were then easily added to the world map as pins using Leaflet JS library. 

## Preview
The project could be viewed <a href="https://tr808.8u.cz/valoch">here</a>. It uses sample <b>Name</b>s and <b>Surname</b>s as I don't think I am allowed to publish contacts' names. 

It has many flaws. Dataset is static (should have been JSON or better SQL), UX is really bad, and pin clustering could be implemented. But I still like this project very much. 