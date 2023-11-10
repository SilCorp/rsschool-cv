# Alexander Silchenko

## Contacts
* **E-mail:** _[alex.silcorp@gmail.com](mailto:alex.silcorp@gmail.com)_
* **LinkedIn:** _[Alexander Silchenko](https://www.linkedin.com/in/alexander-silchenko/)_
* **Github:** _[SilCorp](https://github.com/SilCorp)_

## About Me

An accomplished individual with strong knowledge in web development and 3+ years of experience. Worked on projects in such domains as: E-commerce, FinTech, MedTech. Clear understanding of web development processes. Implementing cross-platform application solutions.

## Skills
* **Languages:** _JavaScript, Typescript, HTML, CSS, SCSS_
* **Libraries:** _React JS, React Router, Redux, Material UI_
* **Testing:** _Jest, React Testing Library_
* **Tools:** _Git, Docker_

## Code examples
**Task:** [RGB To Hex Conversion](https://www.codewars.com/kata/513e08acc600c94f01000001)

**Description:** 
> The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value.

**Solution:**

````
function rgb(r, g, b){
  return Array.from(arguments).reduce((buf, num) => {
    num = num > 255 ? 255 : num;
    num = num < 0 ? 0 : num;
    num = num.toString(16);
    if (num.length < 2)
      num = '0' + num;
      return buf + num.toUpperCase();
  }, "")
}
````


## Work History

### Frontend Developer

**Company:** _Syberry Corporation_

**Dates:** _2022-08 – 2023-08_

**Experience:**
* _Collaborated with stakeholders during development processes to confirm creative proposals and design best practices._
* _Coded using HTML, CSS and JavaScript to develop features for both mobile and desktop platforms._
* _Researched emerging web technologies and trends for possible incorporation into sites._

---

### Frontend Developer

**Company:** _iTechArt Group, Inc._

**Dates:** _2021-06 – 2022-07_

**Experience:**
* _Built a project from scratch using React, Redux._
* _Created layout using HTML , SCSS_
* _Participated in project planning._

## Education

### _Bachelor's Degree: Mathematics And Technologies of Programming_

**_Francisk Skorina Gomel State University – Gomel, Belarus_**

_2015-09 – 2019-06_

## Languages
* **Russian:** _Native (C2)_
* **English:** _Intermediate (B1)_