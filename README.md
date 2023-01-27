# Reagan
## Usage notes
It's not necessary for all links to be contained in a ```<nav>``` element. ```<nav>``` is intended only for a major block of navigation links; typically the <footer> element often has a list of links that don't need to be in a ```<nav>``` element.
A document may have several <nav> elements, for example, one for site navigation and one for intra-page navigation. aria-labelledby can be used in such case to promote accessibility, see example.
<br>
User agents, such as screen readers targeting disabled users, can use this element to determine whether to omit the initial rendering of navigation-only content.
Examples
<br>
In this example, a ```<nav>``` block is used to contain an unordered list ```(<ul>)``` of links. With appropriate CSS, this can be presented as a sidebar, navigation bar, or drop-down menu.
