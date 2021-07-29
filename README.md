# [Change Background color vinilla javascript project](https://kamrulcoder.github.io/change-background-color/)

## This  project is very simple and straightforward.  But i can learn something throught this project. 

## That's  what I  am learning here ........... 

1. **Document.queryseletor()***
1. **Math.Random Method**
1. **ParseInt()**
1. **addEventListener** 
1. **javascript use style** 

<br>

>
> ## Code Preview 

#### Html Code................

```
<div class="background">
        <div class="container  ">
            <div class="background-box  " style=" margin:  100px;">
                <div class="box  d-flex justify-content-center align-items-center  border border-primary  rounded "
                    style="height: 50vh; margin: 0 100px;  background: #000;">
                    <button class="btn btn-primary change-btn">Click Here</button>
                </div>
            </div>

        </div>
    </div>
```
<br> 

### javascript code............

```
let btn = document.querySelector(".change-btn");

        let body = document.querySelector(".box")

        btn.addEventListener("click", function () {
            let color = [
                'red',
                'green',
                "AliceBlue",
                "AntiqueWhite",
                "Aqua",
                "Aquamarine",
                "Azure",
                "Beige",
                "Bisque",
                "Black",
                "BlanchedAlmond",
                "Blue",
                "BlueViolet",
                "Brown",
                "BurlyWood",
                "CadetBlue",
                "Chartreuse",
                "Chocolate",
                "Coral",
            ];

            let colorIndex = parseInt(Math.random()*color.length)
            body.style.background = color[colorIndex]
        })

```


