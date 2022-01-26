# CPNT-260
## Edgar Francis Caballero
### Links:
 - Github Repo: <a href="https://github.com/TSEidolon/cpnt260-a1" target="_blank"> CPNT260-a1 Repo </a>
 - Github Pages Site: <a href="https://tseidolon.github.io/cpnt260-a1/" target="_blank"> Live Page </a>

 ### Reflection:
  - I ran into an <em> overflow </em> problem (Horizonal Scrolling) near the end of working on the assignment.
    - I tried to troubleshoot the problem for an hour searching terms on google such as "how to deal with body overflow css".
     - Landed on this page explaining a great deal on how to fix unintended body overflow <a href="https://css-tricks.com/findingfixing-unintended-body-overflow/" target="_blank"> CSS-Tricks </a>/
      - ```var docWidth = document.documentElement.offsetWidth;
        [].forEach.call(
        document.querySelectorAll('*'),
        function(el) {
        if (el.offsetWidth > docWidth) {
         console.log(el);}});```
       - It places a red border around any overflow problems.
      - <strong> Did not work; I knew <ins> where </ins> the problem was but did not know what the problem <ins> was </ins> </strong>.
       - Turns out the background width of the background image was causign the overflow (changed `width:100%` to commenting it out `line 2 in style.css`).


### Flare:
 - Added hover css classes `Lines 60-71 in style.css`.

<h3> Attributions <h3>
    <li> &copy; <a href="https://www.hogwartslegacy.com/en-gb" target="_blank"> Hogwarts Legacy, 2020</a>  </li>
    <li>&copy; <a href="https://harrypotter.fandom.com/wiki/Hogwarts_School_of_Witchcraft_and_Wizardry?file=Hogwartscrest.png" target="_blank">Wikipedia, Hogwarts Crest, 2021</a></li>
    <li>&copy; <a href="https://harrypotter.fandom.com/wiki/Hogwarts_School_of_Witchcraft_and_Wizardry"> Wikipedia, Hogwarts School of Witchcraft and Wizardry, 2021</a></li>
    <li>&copy; <a href="https://harrypotter.fandom.com/wiki/Hogwarts_School_of_Witchcraft_and_Wizardry?file=OfficialHogwartsMap.jpg"> Wikipedia, Hogwarts Grounds, 2014</a></li>
    <li>&copy; <a href="https://www.pngwing.com/en/free-png-pzwks"> PNGWING, Hogwarts PNG, 2021</a></li>
    <li>&copy; <a href="https://harrypotter.fandom.com/wiki/Hogwarts_School_of_Witchcraft_and_Wizardry?file=Outstanding_WOMBAT.jpg"> Wikipedia, WOMBAT Grades, 2021</a></li># cpnt260-a1
