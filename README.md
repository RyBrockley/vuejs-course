# VueJs Course progress with The Net Ninja
___

### Udemy Course by The Net Ninja


## Create a VUE Instance in app.js

```
new Vue({
    el: '#app',
    data: {
        name: 'Ryan'
    }
})
```

### The HTML looks like this in index.html

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
  
    <title>Vue Course</title>
</head>

<body>
    <h1>Vue Basics</h1>
    <div id="app">
        <h2>{{ title }}</h2>
        

    </div>

    <script src="app.js"></script>
</body>

</html>
```