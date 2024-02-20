
# Calender

This is Calender using HTML, CSS and Java-Script.





## HTML

```html
<div class="hero">
        <div class="calender">
            <div class="left">
                <p id="date">01</p>
                <p id="day">Sunday</p>
            </div>
            <div class="right">
                <p id="month">Janurary</p>
                <p id="year">2024</p>
            </div>
        </div>
    </div>
```

# css
```css
.hero{
    width: 100%;
    min-height: 100vh;
    background: #000;
    display: flex;
    align-items: center;
    justify-content: center;
}
.calender{
    width: 300px;
    height: 250px;
    background: #fff;
    display: flex;
    align-items: center;
    border-radius: 10px;

}
.left, .right{
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    flex-direction: column;
}
.right{
    width: 42%;
    background: rgb(107, 0, 0);
    color: #fff;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
}
.left{
    width: 58%;
}
#date{
    font-size: 100px;
    line-height: 90px;
}

```

## Java-Script
```javascript
const date = document.getElementById("date");
        const day = document.getElementById("day");
        const month = document.getElementById("month");
        const year = document.getElementById("year");
        const today = new Date();
        const weekdays = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
        const allmonths = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];

        date.innerHTML =(today.getDate()<10?"0":"") + today.getDate();
        day.innerHTML =weekdays[today.getDay()];
        month.innerHTML =allmonths[today.getMonth()];
        year.innerHTML =today.getFullYear();
```
## 🔗 Social Media Links
[![instagram](https://img.shields.io/badge/instagram-black?logo=instagram&logoColor=white&link=https%3A%2F%2Fwww.instagram.com%2Fadityamishras%2F)](https://www.instagram.com/adityamishras/)
