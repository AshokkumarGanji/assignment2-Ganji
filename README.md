# assignment2-Ganji
# Ashok Kumar Ganji
###### Cricket

My favourite game is cricket. It is a **popularly played sport throughout the world!** The best teams from every country make it to the world cup, and people across the globe watch it with interest. **I love cricket because** there is a sense of freedom in playing the game.

---
## Favourite IPL franchise
#### Chennai Super Kings

1. Ms Dhoni
2. Ravindra Jadeja
3. Suresh Raina

#### Unorder Lists
- Mumbai Indians
- Sunrisers Hyderabad
* Delhi Capitals
* Gujarat Titans

[AboutMe](AboutMe.md)

---
#### Table

This table contains the information about 3 different countries and the table first column should be the name of a country, second column should be the reason why you recommend it and The third column is how many days you would spend there. 

|      Country      |        Reason                        |         No.of days         |
|-------------------|--------------------------------------|----------------------------|
|      India        |     Good Food                        |              90            |
|      Italy        |     rich history vibrantculture      |              60            |
|       USA         |     World class  Museums             |              50            |

---
#### Pithy quotes

>Life is not a problem to be solved, but a reality to be experience. 
-*James Joyce*

>Everything comes in time to him who knows how to wait. 
-*Leo Tolstoy*

---
#### Code Fencing 

![Link to Stackoverflow](https://stackoverflow.com/questions/70218486/how-to-replicate-fence-svg-as-a-gradient)
```
<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>
```
![Link to SVG patterns](https://css-tricks.com/snippets/svg/svg-patterns/)


