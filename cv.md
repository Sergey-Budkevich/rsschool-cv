# Sergey Budkevich
## Contact information:
* **Phone, Viber** +375(29)537-17-30
* **E-mail:** sergeybudkevich1997@gmail.com
* [LinkedIn](https://www.linkedin.com/in/sergey-budkevich/)
* [GitHub](https://github.com/Sergey-Budkevich)
* **Address:** Minsk, Belarus
---

## About myself:
I chose this direction because I like to create and see the result of my work. I started my learning with John Ducket's book "HTML and CSS". Convinced that I really like this direction, I took courses and continue to expand my knowledge through articles and YouTube. I enjoy writing code and dealing with bugs. I am purposeful, responsible, friendly and calm in relation to routine work. I consider the strong side of my character to be the constant desire to learn new things, improve the knowledge already gained and be the best in my field.

---

## Hard skills: 
* HTML
* CSS, SCSS
* JavaScript
* TypeScript
* React
* Redux, Redux Toolkit
* React-router
* Git
* Webpack
---

## Code example: 
**Detect Pangram:** A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant).

Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

```
function isPangram(str){
  return new Set(str.toLowerCase().split('').filter(item => item >= 'a' && item <= 'z')).size == 26
}
```
---