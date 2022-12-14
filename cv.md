# Victoria Kovaliova

### My Contact Info

-   **Telegram** [Виктория](https://t.me/Vikenya)
-   **E-mail:** [victkovaliova@gmail.com](victkovaliova@gmail.com)
-   **LinkedIn:** [victoria-kavaliova](https://www.linkedin.com/in/victoria-kavaliova/)
-   **GitHub:** [vikentia](https://github.com/vikentia)

---

### About Me

I am 31 years old, I work as an entrepreneur for some years.
I am interested in web development because this profession provides opportunities for professional growth and remote work.
I’m hardworking, tactful, fair, reliable, active, helpful for my team.
I’m very flexible and adaptable to new situations.
My goal is to gain knowledge in the field of front-end development.

---

### Skills:

-   JavaScript
-   TypeScript
-   React, Redux
-   HTML5, CSS3
-   Git, GitHub
-   VS Code

---

### Code Example

**KATA from CODEWARS:**
_You are given a string of numbers between 0-9. Find the average of these numbers and return it as a floored whole number (ie: no decimal places) written out as a string. Eg: "zero nine five two" -> "four". If the string is empty or includes a number greater than 9, return "n/a"_

```javascript
function averageString(str) {
    if (!str) return "n/a";
    let numbers = [
        "zero",
        "one",
        "two",
        "three",
        "four",
        "five",
        "six",
        "seven",
        "eight",
        "nine",
    ];
    let sum = str
        .split(" ")
        .map((item) => {
            if (numbers.includes(item)) {
                return numbers.indexOf(item);
            } else {
                return "n/a";
            }
        })
        .reduce((acc, item) => acc + item, 0);
    return numbers[Math.floor(sum / str.split(" ").length)] || "n/a";
}
```

---

### Courses:

-   Redev Course
-   JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/)
-   RS Schools Course «JavaScript/Front-end. Stage 0»

---

### Languages:

-   Russian \- Native
-   English \- B1
