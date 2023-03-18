# CSS Grid

## Learning Objectives
1. Copare the basics between Flexbox and Grid
2. Decribe a situation for using Grid over Flexbox

## CSS Grid Basic
display: grid;
gird-template-column:10px 10px;
gird-template-row:10px 10px;
gird-template:10px 10px / 10px 10px; 

## Positiong Grid Elements

<!-- * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  display: grid;
  height: 100vh;
  grid-template: 20% 20% 20% 20% 20% / 20% 20% 20% 20% 20%;
  background-color: lightblue;
}

.room {
  border: 1px solid black;
  font-size: 50%;
  text-align: center;
}

.living-room {
  grid-area: 1 / 1 / 3 / 6;
}

.kitchen {
  grid-column: 4 / 6;
  grid-row: 3 / 6;
}

.bathroom {
  grid-column-start: 1;
  grid-column-end: 2;
  grid-row-start: 3;
  grid-row-end: 6;
}

.bedroom {
  grid-column: 2 / 4;
  grid-row: 3 / 5;
}

.closet {
  grid-column: 2 / 4;
  grid-row: 5 / 6;
} -->

<!-- 
.living-room {
 grid-column-start: 1;
 grid-column-end: 6;
 grid-row-start:1;
 grid-row-end:3;
}

.kitchen{
  grid-column-start: 4;
  grid-column-end: 6;
  grid-row-start: 3;
  grid-row-end: 6;
}

.bathroom {
  grid-column-start: 1;
  grid-column-end: 2;
  grid-row-start: 3;
  grid-row-end: 6;
}

.beedroom {
  grid-column: 2 / 4;
  grid-row: 3 / 5;
}


.closet {
  grid-column: 2 / 4;
  grid-row: 5 / 6;
}

https://www.youtube.com/watch?v=rg7Fvvl3taU
 -->


# Advance CSS Grid Positioning

## Learning Objectives

1. Create mulitple grid tracks more easily using the repeat function
2. Create grid tracks using `fr` unis instead of an explicit size.
3. Se minimun, maximum, and ideal track size bounderies
4. Use `auto-fit` and `auto-fill` to create 