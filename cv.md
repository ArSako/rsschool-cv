# Artur Sanko #

## Contacts: ##
* **Phone:** +375 29 518 73 86
* **E-mail:** sanko.artur84@gmail.com
* **Github:** [ArSako](https://github.com/ArSako)
* **Telegram:** [SankoA](https://t.me/SankoA)

## About me ##
I am 22 years old, I am from Grodno. I graduated from the university in the summer of 2022. I want to become a front-end developer. I think that my perseverance and discipline will help me in this.

## Skills ##
* **HTML5** 
* **CSS3**
* **JavaScript (Basics)**
* **Git**
* **VS Code**

## Code Example: ##
**Description**
*A Narcissistic Number is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base. In this Kata, we will restrict ourselves to decimal (base 10).*
*For example, take 153 (3 digits), which is narcisstic:*

1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153

*and 1652 (4 digits), which isn't:*

1^4 + 6^4 + 5^4 + 2^4 = 1 + 1296 + 625 + 16 = 1938:

`
    function narcissistic(value) {
        var saar = [];
        var arr = (""+value).split("").map(Number)
        for (var i = 0; i < arr.length; i++){
        saar.push(Math.pow(arr[i],arr.length));
        }
        let res = saar.reduce(function(sum, elem) {
        return sum + elem;
    }, 0);
        return (value == res) ? true : false;   
    }
`

## Education ##
**Yanka Kupala State University of Grodno:** Faculty of Mathematics and Informatics 

## Languages: ##
* **Russian** - Native speaker
* **English** - Elementary (Pre-Intermediate in process)
* **Belarusian** - Intermediate
* **Polish** - Basic