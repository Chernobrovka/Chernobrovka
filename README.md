# Dmitry Homan

**Web Developer**
****

<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/dima-goman-9818a7229/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://web.telegram.org/@Chernobrovka1">
    <img src="https://img.shields.io/badge/Telegram-green?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="your-URL">
    <img src="https://img.shields.io/badge/Twitter-red?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<div id="counter" align="center">
  <img src="https://komarev.com/ghpvc/?username=Chernobrovka&style=flat-square&color=blue" alt=""/>  
</div> 

# About Me:

<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>

# Contact information:

* E-mail: gomhu72@gmail.com
* Telegram: https://web.telegram.org/@Chernobrovka1
* LinkedIn: https://www.linkedin.com/in/dima-goman-9818a7229/

****
# Education:

* Belarusian State Technology University
* 2020-2024
* Automation Engeneer

****

# Skills:

* HTML5, CSS3
* JavaScript
* Git, GitHub, Basics of OOP
* C/C++ (for Embedded systems), Electronics

****

# Courses:

* JavaScript Manual on learnjavascript.ru
* JS / Html / CSS on CodeBasics
* RS-School stage 1 (in progress)

****

# Languages:

* Russian
* English (A2)

****

# Code Example:

**The solution to the task CodeWars:**

**Task( 6 Kui ):** You will be given a list of objects. Each object has type, material, and possibly secondMaterial. The existing materials are: paper, glass, organic, and plastic.

Your job is to sort these objects across the 4 recycling bins according to their material (and secondMaterial if it's present), by listing the type's of objects that should go into those bins.

```
function recycle(array) {
  var arr_materails=['paper','glass','organic','plastic'];  
  var arr_baskets=[];
  for(let j=0;j<4;j++) {
    arr_baskets.push(new Array());
  }
  array.forEach(function callback(elem, i, arr) 
  {
    for(let j=0;j<4;j++) 
    {
      var needAddToBasket = false;
      if (elem.material === arr_materails[j])  {
        needAddToBasket = true;
      }
      if (elem.hasOwnProperty ('secondMaterial')) {
        if (elem.secondMaterial === arr_materails[j]) {
          needAddToBasket = true;
        }
      }
      if(needAddToBasket) {
        arr_baskets[j].push(elem.type);
      }
    }
  });
  return arr_baskets;
}

```
