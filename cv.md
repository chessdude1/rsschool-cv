# rsschool-cv
## Dmitry Platonov
## Frontend Developer

### Contact information:
* **Phone** : +79017462648
* **E-mail** : mitia.platonow2011@yandex.ru
* **Telegram** : @Platon_nation

### About me:
 I am currently a first year graduate student. For a deeper understanding of programming, I entered the direction: software engineering. My goal is to become a good developer who deeply understands the technologies he works with.

  I am recently in web development, 6 months. But I can say that these half a year I have been doing something that arouses great interest in me. Most of all I like writing javaScript scripts. Before web development, I tried myself in ML and DataScience, but a lot of mathematics pushed me away from this direction. During these half a year, I got acquainted with such technologies as: React, Redux, HTML5, JavaScript, Next.js, Typescript. Created an application in React + redux, several landing pages, few javaScript applications.
  
  I am sure that hard work, motivation, learn ability will allow me to achieve any goals that I set. And ambition will not allow me to stand still and be constantly in development.
  
 ### Skills:
 1. JavaScript
 2. HTML5
 3. CSS(Preprocessor SCSS)
 4. React JS, Redux( begin level knowledge)
 5. Version control: Git (remote service GitHub)
 6. Next.js
 
  ### Code example:
  **The Hashtag Generator** *The marketing team is spending way too much time typing in hashtags.
Let's help them with our own Hashtag Generator!*

*Here's the deal:*
* It must start with a hashtag (#).
* All words must have their first letter capitalized.
* If the final result is longer than 140 chars it must return false.
* If the input or the result is an empty string it must return false.
```
 function generateHashtag(str) {
  let splitString = str.split("");
  if (splitString[0]) {
    splitString[0] = splitString[0].toUpperCase();
  }
  for (let i = 0; i + 1 < splitString.length; i++) {
    if (splitString[i] === " ") {
      splitString[i + 1] = splitString[i + 1].toUpperCase();
    }
  }
  let StringWithAllUpperCase = splitString.join("");
  let FinalWord = "#".concat(StringWithAllUpperCase.split(" ").join(""));
  if (FinalWord.length > 140 || FinalWord.split("")[1] == undefined) {
    return false;
  }
  return FinalWord;
}
```

