```javascript
//REVISIONS
// Declarez une variable nommée "boucler" contenant true
var boucler = true

// Declarez un tableau members contenant Aida67, lapie002, anneserrano, Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc, patatobeur, Sam11360, elo062, hermeline, Biciclet,
var members=["Aida67","lapie002","anneserrano","Jennysmille","nunkabuk","RCosson","kaonb-ax","FerEmilie","crazychouwi","KiluaZoldyc","patatobeur","Sam11360","elo062","hermeline","Biciclet"];
// SI la variable boucler vaut true ALORS
var check = document.getElementById('check');
check.addEventListener("click",function(){
  if (boucler=true){
    // Bouclez sur le tableau que vous avez déclaré ci-dessus
    for(var i = 0; i < members.length; i++){
      switch (members[i]) {
        case "crazychouwi":
        var div = document.createElement("div");
        var check = document.getElementById("check");
        div.innerHTML = "affiche"+" "+"crazychouwi";
        check.appendChild(div);
        console.log("affiche"+" "+"crazychouwi");
        break;
        default:
        var div = document.createElement("div");
        var check = document.getElementById("check");
        div.innerHTML = members[i];
        check.appendChild(div);
        console.log(members[i]);
      }
    }
  }

})
  // Mettre un switch pour qu'au moment où la boucle se trouve sur votre pseudo cela ajoute "Affiche " devant votre pseudo dans la console et sur l'écran et par defaut seulement le pseudo des autres

// FIN REVISIONS

// COURS AJAX
  // AJAX Jquery .ajax() ou .get()
  // Faites une requete vers l'API REST de Github pour récupérer les informations de votre compte


// FIN COURS AJAX

```
