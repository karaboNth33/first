My project was Css Grid game here are the specifications:
CSS Grid Game with Game Logic (Karabo):
Elevate the CSS grid game project by adding game logic using HTML and CSS only.
Create complex puzzle challenges with win/lose conditions entirely controlled by CSS. Implement game state transitions and feedback animations for a more immersive experience.
I used CSS grid to create a 4x4 grid and used css to style my game but I had one major problem.
I couldn't find a way to apply HTML and CSS logic on game I searched dozens of forums and pages but the closest I got to a solution was post on DEV.to(https://dev.to/iamschulz/writing-logic-in-css-3ig0)
The author suggested one can use data-attributes to form conditions:

<code>
[data-attr='true'] {
    /* if */
}
[data-attr='false'] {
    /* elseif */
}
:not([data-attr]) {
    /* else */
}
</code>

but the problem I had with this solution is that I found it difficult to compare the data-attribute to a variable here's a pseudocode example of what I mean,

<code>
  String Answer= "grid-column-start: 3;"
  Input= "grid-column-start: 3;"
  answer=Input
  
</code>
