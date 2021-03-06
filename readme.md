
[![npm](https://img.shields.io/npm/dt/v-owl-carousel.svg)](https://www.npmjs.com/package/v-owl-carousel)

  ---

## :snowflake: Intro





- The [VueJS](https://vuejs.org/) wrapper for [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/).





- [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/) is touch enabled jQuery plugin that lets you create a beautiful responsive carousel slider.






## :snowflake: Installation





`npm i v-owl-carousel` or `yarn add v-owl-carousel`



## :snowflake: Usage


`import carousel from 'v-owl-carousel'`


```

<carousel>

  <img src="https://placeimg.com/200/200/any?1">

  <img src="https://placeimg.com/200/200/any?2">

  <img src="https://placeimg.com/200/200/any?3">

  <img src="https://placeimg.com/200/200/any?4">

</carousel>

```

Set options,

```

<carousel :autoplay="true" :nav="false>

//

//

</carousel>

```



## Available options





Currently following options are available.



##### *(More to come)*





- ### items





type : `number`




default : `3`




The number of items you want to see on the screen.





- ### margin





type : `number`




default : `0`




Margin-right (px) on item.





- ### loop





type : `boolean`




default : `false`




Infinity loop. Duplicate last and first items to get loop illusion.





- #### center





Type: `Boolean`




Default: `false`





Center item. Works well with even an odd number of items.





- #### nav





Type: `Boolean`




Default: `false`




Show next/prev buttons.





- #### autoplay





Type: `Boolean`




Default: `false`




Autoplay.





- #### autoplaySpeed





Type: `Number/Boolean`




Default: `false`




Autoplay speed.





- #### rewind





Type: `Boolean`




Default: `true`




Go backwards when the boundary has reached.




- #### mouseDrag




Type: `Boolean`




Default: `true`




Mouse drag enabled.




- #### touchDrag




Type: `Boolean`




Default: `true`




Touch drag enabled.




- #### pullDrag




Type: `Boolean`




Default: `true`





Stage pull to edge.




- #### freeDrag




Type: `Boolean`




Default: `false`




Item pull to edge.





## :collision: NPM





[![NPM](https://nodei.co/npm/v-owl-carousel.png)](https://www.npmjs.com/package/v-owl-carousel)
