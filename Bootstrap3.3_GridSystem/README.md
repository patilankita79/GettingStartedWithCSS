# Grid System

<hr>
Every container in bootstrap can be divided into 12 columns. Using grid system, we can decide how many of the 12 columns each element should take up
<br>

<strong>Key Points: </strong>
<ul>
  <li>Grid systems are used for creating page layouts through a series of rows and columns that house your content. Every time you use bootstrap grid, it needs to be inside container</li>
  <li>There are 4 sizes ->  large(lg), medium(md), small(sm), extra small(xs)</li>
  <li>You can re-assign those 12 units at 4 different breakpoints(those 4 different sizes) to get responsive layout depending on the scrren size </li>
</ul>


To divide the large screen into 4 columns: (Calculation=> 12 units / 4 = 3 )
Therefore, we will designate 3 units

```
<div class="container">
    <div class="row">
	      <div class="col-lg-3"></div>
        <div class="col-lg-3"></div>
        <div class="col-lg-3"></div>
    </div>
</div>
```
