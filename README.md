

# ✅ **1. Déclarer x = 10 et l’afficher avec document.write**

```js
let x = 10;                  // On crée une variable x et on lui donne la valeur 10
document.write(x);          // On écrit la valeur directement dans la page
```

---

# ✅ **2. Afficher un prénom dans la console**

```js
let prenom = "Mounir";      // Variable contenant un prénom
console.log(prenom);        // Affiche la valeur dans la console du navigateur
```

---

# ✅ **3. const age + alert**

```js
const age = 20;             // Création d’une constante age
alert(age);                 // Affiche une fenêtre pop-up avec 20
```

---

# ✅ **4. Modifier un paragraphe avec innerText**

HTML :

```html
<p id="p1">Texte original</p>
```

JS :

```js
document.getElementById("p1").innerText = "Nouveau texte";  
// On récupère le paragraphe p1 puis on remplace son texte
```

---

# ✅ **5. Remplir un paragraphe vide avec innerHTML**

HTML :

```html
<p id="msg"></p>
```

JS :

```js
document.getElementById("msg").innerHTML = "<strong>Message important</strong>";
// innerHTML permet d’insérer du HTML (ici texte en gras)
```

---

# ✅ **6. Changer la source d’une image**

HTML :

```html
<img id="photo" src="ancien.jpg">
```

JS :

```js
document.getElementById("photo").src = "nouveau.jpg";
// On remplace l'image affichée en modifiant src
```

---

# ✅ **7. Bouton + alert**

HTML :

```html
<button id="btn">Clique</button>
```

JS :

```js
document.getElementById("btn").onclick = function () {
    alert("Bonjour");       // S'affiche au clic
};
```

---

# ✅ **8. Changer la couleur d’un paragraphe**

```js
var color = "blue";                     // Variable couleur
document.getElementById("p1").style.color = color;
// On applique la couleur au texte du paragraphe
```

---

# ✅ **9. Modifier innerText d’un div**

HTML :

```html
<div id="box"></div>
```

JS :

```js
document.getElementById("box").innerText = "Contenu modifié";
// innerText : insère du texte simple
```

---

# ✅ **10. Message console à l’ouverture**

```js
console.log("La page est chargée");  
// Affiche un message dans la console
```

---

# ✅ **11. Image vide → lui donner un src**

HTML :

```html
<img id="img">
```

JS :

```js
document.getElementById("img").src = "image.jpg";
// L’image apparaît grâce à la nouvelle source
```

---

# ✅ **12. Changer taille du texte**

```js
document.getElementById("p1").style.fontSize = "24px";
// On modifie la propriété CSS font-size
```

---

# ✅ **13. Remplacer un texte avec textContent**

```js
document.getElementById("p1").textContent = "Texte remplacé";
// textContent met uniquement du texte (pas de HTML)
```

---

# ✅ **14. document.writeln deux lignes**

```js
document.writeln("Ligne 1");     // Écrit une ligne
document.writeln("Ligne 2");     // Puis une seconde
```

---

# ✅ **15. let note = 15 + innerHTML**

HTML :

```html
<p id="info"></p>
```

JS :

```js
let note = 15;                                       // Variable
document.getElementById("info").innerHTML = note;    // Écriture dans le paragraphe
```

---

# ✅ **16. Changer backgroundColor**

```js
document.getElementById("box").style.backgroundColor = "yellow";
// Fond jaune
```

---

# ✅ **17. Bouton → changer texte d’un paragraphe**

HTML :

```html
<p id="p1">Ancien texte</p>
<button id="btn">Changer</button>
```

JS :

```js
btn.onclick = function () {
    p1.innerText = "Texte changé";       // Le texte change au clic
};
```

---

# ✅ **18. Variable image + changer src**

```js
let imgName = "photo.jpg";                 // Variable contenant le nom du fichier
document.getElementById("photo").src = imgName;
// On utilise la variable pour l’image
```

---

# ✅ **19. Mettre un message d’accueil**

```js
document.getElementById("info").innerText = "Bienvenue sur la page";
// Remplace le texte du paragraphe
```

---

# ✅ **20. Afficher le type d’une variable**

```js
let x = "test";
console.log(typeof x);                 // Affiche "string"
```

---

# ✅ **21. Image grise → couleur au clic**

HTML :

```html
<img id="p" src="gris.jpg">
<button id="b">Couleur</button>
```

JS :

```js
b.onclick = function () {
    p.src = "couleur.jpg";            // Nouvelle image
};
```

---

# ✅ **22. Mettre texte en italique**

```js
document.getElementById("p1").style.fontStyle = "italic";
// Le texte passe en italique
```

---

# ✅ **23. Variable phrase + alert**

```js
let phrase = "Bonjour tout le monde";  
alert(phrase);                          // Affiche la phrase
```

---

# ✅ **24. Bouton → document.write**

```js
document.getElementById("show").onclick = function () {
    document.write("Message affiché");
    // ATTENTION : remplace toute la page
};
```

---

# ✅ **25. Trois variables + console**

```js
let nom = "Ali";      
let age = 22;
let pays = "Algérie";
console.log(nom, age, pays);       // Affichés dans la console
```

---

# ✅ **26. innerHTML + strong**

```js
document.getElementById("info").innerHTML = "<strong>Texte important</strong>";
// innerHTML permet d’ajouter du HTML (gras)
```

---

# ✅ **27. Image vide → src au clic**

HTML :

```html
<img id="im">
<button id="btn">Afficher image</button>
```

JS :

```js
btn.onclick = function () {
    im.src = "photo.jpg";          // L’image apparaît au clic
};
```

---

# ✅ **28. Modifier la largeur d’un div**

```js
document.getElementById("box").style.width = "200px";
// Le div s’élargit
```

---

# ✅ **29. Variable message + paragraphe**

```js
let message = "Bienvenue";  
document.getElementById("p1").innerText = message;
// On affiche la variable dans le paragraphe
```

---

# ✅ **30. Bouton → texte du paragraphe rouge**

```js
btn.onclick = function () {
    document.getElementById("p1").style.color = "red";  
};
```

---

