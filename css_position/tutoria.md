## positioning in css
* static
* absolute 
* relative
* fixed

### demonstrate absolute and relative position
markup 
~~~html
<body>
  <div class="parent">
    <div class="child">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet vero accusamus, praesentium nobis deserunt aspernatur distinctio debitis dolores possimus ipsa delectus doloribus recusandae, consequuntur minima reprehenderit quisquam reiciendis nulla labore!</p>
    </div>
  </div>
  <div class="uncle">
    <h1>uncle</h1>
  </div>
</body>
~~~

css part
~~~css
body {
  margin: 0;
  padding: 0;
  position: relative;
}
.uncle {
  position: absolute;
  top: 50px;
  left: 100px;
}
~~~


## combinator in css
* descendant selector (space)
~~~css
.parent .child {

}
~~~
* child selector (`>`)
~~~css
.parent > .child {

}
~~~
* adjacent sibling selector (`+`)
~~~css
.brother + .nearest_brother {

}
~~~
* general sibling selector (`~`)
~~~css
.css {
  .brother ~ .all_brother {

  }
}
~~~





