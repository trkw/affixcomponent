
# affixcomponent

**affixcomponent.js is supported in all modern browsers**

**html:**

```html
<div  class="my-element"
      data-affix="init"
      data-offset-top="auto"
      data-offset-bottom="50"
      data-offset-top-element="auto"
      data-offset-bottom-element=".footer"
      data-mobile-screen-width="auto"
>

.... content ....

</div>
```

```html
data-affix                  | init
data-offset-top             | number   | auto (parent container top) 
data-offset-bottom          | number   | auto (100)        
data-offset-top-element     | selector | auto (none)  
data-offset-bottom-element  | selector | auto (none)  
data-mobile-screen-width    | number   | auto (992)            
```

**css:**

```css
.my-element{

}

.my-element.affix-mobile-view{

}
```


**Requirements:**
* jQuery

**CDN:**
```
[production] https://cdn.rawgit.com/TigranSimonyan/affixcomponent/879dcdcb/affixcomponent.min.js
[development] https://rawgit.com/TigranSimonyan/affixcomponent/master/affixcomponent.min.js
```


