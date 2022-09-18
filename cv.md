# Albert Lavrinov

## Contact information:

- **Email:** albert.lavr@gmail.com
- **Telegram:** @jokeonyou94
- [VKontakte](https://vk.com/alik_man94)

## About myself:

The first time I met programming languages at a summer camp, when I was about 15 years old. My first programming language was Pascal. It was really interesting and exciting for me. Unfortunately, I did not have a good teacher in my school for keep my new hobby. Thats why I forgot about programming languages for long years.

Three years ago I decided to continue studying programming languages as a my new hobby. I started by learning HTML and CSS to create my own web-sites. It was I little bit hard, because I am a chemist. But I really liked doing it after my main job.

After two years, I started to create beautiful web-sites and then I understood, that I want to work as a front-end developer. But my knowledge was not enough for that. And I resolved to learn Java Script to improve my skills.

Today I can create web-sites and know the basics of JS. I believe that with my responsibility and great desire, I will become a front-end developer.

## My skills:

- HTML5, CSS3
  - Flexbox
  - Grig Layout
- Photoshop
- Figma
- JavaScript Basics
- VS Code

## Code example:

**Detect Pangram Kata from Codewars:** A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant). Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

**_My solution:_**

```
function isPangram(string){
  let letters = new Set();

  for (let i = 0; i < string.length; i++) {
    let letter = string[i].toLowerCase();

    if (/[a-zA-z]/.test(letter)) {
      letters.add(letter);
    }
  }

  return Array.from(letters).length === 26;
}
```
