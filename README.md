# [Diktáty.cz](https://cestina.diktaty.cz) solver
Napíše správné odpovědi na diktaty.cz

# kód
```js
var vysledky = "Odpovedi: "
document.getElementById("spravny_vysledek_celkem").value.split("#").forEach(v => vysledky += v + ", ")
document.querySelectorAll('[for="postupPrace"]')[0].innerHTML = vysledky
document.querySelectorAll('[for="postupPrace"]')[0].style.fontSize = "29px"
```

# návod
> Klikni `F12` a tam napiš kód který máš tady ^
