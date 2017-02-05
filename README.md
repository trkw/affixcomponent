
# affixcomponent

**affixcomponent.js is supported in all modern browsers**

[Demo] https://tigransimonyan.github.io/affixcomponent/

**html:**

```html
<div  class="my-element"
      data-affix="init"
      data-mobile-screen-width="auto"
      data-offset-top="auto"
      data-offset-top-from="auto"
      data-offset-bottom="50"
      data-offset-bottom-from=".footer"
>

.... content ....

</div>
```

```html
data-affix                  | init
data-offset-top             | number   | auto (parent container top) 
data-offset-top-from        | selector | auto (none)  
data-offset-bottom          | number   | auto (100)  
data-offset-bottom-from     | selector | auto (none)  
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


