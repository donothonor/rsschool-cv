# **Spiridonov Vadim**
 **Contact :**
 
 Phone : +7 (996)  728-91-58
 
 VK    : https://vk.com/spleeeeeeen


## **About myself**

My purpose is to learn to code corectly and efficiently. I want to learn more and more, coding become a part of my life.  I aspire to work at EPAM.

## **Skills**

Basics HTML, CSS, JavaScript.
### **Code examples**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гонки</title>
</head>
<body>
    <script src="https://code.jquery.com/jquery-2.1.0.js"></script>
    <script>
        var Car = function (x, y) {
            this.x = x;
            this.y = y;
        };

        var drawCar = function (car) {
            var carHtml = '<img src="/100.png" alt="">';

            var carElement = $(carHtml);

            carElement.css({
                position: "absolute",
                left: car.x,
                top: car.y
            });
            $("body").append(carElement);
        };
        
        var tesla = new Car(20, 20)
        var nissan = new Car(100,200)
        drawCar(tesla);
        drawCar(nissan);

    </script>
    
</body>
</html>

```



