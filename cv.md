# Andrey Chernukho

### Contact Info

 **Phone number:**  +375 (29) 504-33-30

 **E-mail:** andrei.chernukho.86@gmail.com

 **Skype:** chernuho1986

### Summary

Self-motivated, organized and competent 'Junior Programmer' is looking for a suitable **JavaScript position**, where I can improve my skillset in web technologies to develop and implement solutions to meet business needs.

### Skills

* JavaScript
* HTML
* CSS
* Java SE
* SQL
* Git
* Visual Studio Code
* Intellij IDEA
* Jira
* MySQL

### Code examples (LATEST)

```javascript
/**
 * @param preferences - an array of integers. Indices of people, whom they love
 * @returns number of love triangles
 */
module.exports = function getLoveTrianglesCount(preferences = []) {
  let count = 0;

  for (let i = 0; i < preferences.length; i++) {
    let spichoneeA = preferences[i];
    let spichoneeB = preferences[spichoneeA - 1];
    let spichoneeC = preferences[spichoneeB - 1];

    let isDifferent = spichoneeA != spichoneeB && spichoneeB != spichoneeC && spichoneeA != spichoneeC;

    if (spichoneeC - 1 == i && isDifferent) {
      count++;
    }
  }

  return count / 3;
};
```

### Experience

[Javarush](https://javarush.ru/users/2021131) tasks and games.

### Education

2019 **[Сodecademy](https://www.codecademy.com/profiles/6185991363)**

2019 **[Javarush](https://javarush.ru/users/2021131)**

2018 **QA Academy**, Basics of Software Testing (Reference Letter)

2018 **Streamline**, General English Course at Intermediate level

2017 **Streamline**, General English Course at Pre-Intermediate level

2010 **Belarusian National Technical University**
Marketing, management and entrepreneurship faculty, Industrial Economics and Project Management

2008 **Belarusian National Technical University**
Mining engineering and engineering ecology faculty, Mining Machines

### English

**Level:** Intermediate.
