__Disclaimer: This documentation are supposed for personal purpose. On each perspective or any different kind of public purpose are allowed And if you use this
make sure that you can be able with javascript language, if not, you need to seed javascript basic syintax that spread out on youtube or google :)__
# Vue js Directive

## Explanation

Vue directive as simple for interactive User Interface that user see it.

## Example

before we try it. lets take a look for each example on each directive here. I'll use cdn for current example. Let's make index.html or whatever you want naming the file. And create a basic html.
```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <style media="screen">
      ...
    </style>
  </head>
  <body>
    ...
  </body>
</html>

```
Import Vue cdn and put it into before closing of body tag.
```
   ...
    <script src="https://unpkg.com/vue@next"></script>
    <script>
      // vue script
      ...
    </script>
  </body>
```
Below ```// vue script``` let's add this code. We create simple vue app from Vue on cdn that we imported above. inside of ```createApp``` we return it the
data of 
```
let app = Vue.createApp({
  data: function(){
    return {
      greeting: 'Hello Rejka',
      isVisible: true,
      isVisible2: false
    }
  }
})
```





### - ```v-if```

### - ```v-model```



