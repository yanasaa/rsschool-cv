# Yana Matyushenko
## Front-End Developer
![avatar](https://yana-matyushenko.vercel.app/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FmyPhoto.8d58ca5e.png&w=256&q=95)
********
### Contacts
* _e-mail:_ __yanasaa@hmail.com__ 
* _discord:_ __yanasaa__ 
********
### About Me
Hello,

My name is Yana, and I am an aspiring __frontend developer__. Although my work experience is limited, I am well-acquainted with team collaboration. I have a passion for creating _aesthetically pleasing and user-friendly interfaces_. In my projects, I primarily use __React (JavaScript)__.
********
### Skills
React, JavaScript, HTML, CSS, TypeScript, Git, Tailwind, Ant Design, Redux Toolkit, English, Scrum
********
### Code Example
``` 
import { FC, useEffect } from "react";
import s from "./HeadAnimation.module.scss";

const HeadAnimation: FC = () => {
  const accentWords: string[] = ["best", "your", "fun", "new"];

  useEffect(() => {
    const accentBlock = document.querySelector(`${s.accent}`)
    const accentWords: NodeListOf<HTMLElement> = document.querySelectorAll(".anim")
  })

  return (
    <div className={s.animation}>
      <div className={`${s.accent}`}>
        {accentWords.map((word, i) => <p className={`${s[word]} anim`} key={i}>{word}</p>)}
      </div>
    </div>
  );
};

export default HeadAnimation;
```
********
### Experience and Education
* __Курс "JavaScript/DOM/Интерфейсы"__
_learn.javascript.ru_
Courses in professional JavaScript and related technologies. With theory, practice and "code review"

* __Qa Automation Engineer__
_Red Rover School_
Courses in  theory of software testing, as well as automation using JavaScript and Cypress. There I supervised a group of students as part of a course on learning the basics of JavaScript

* __Front-End Developer__
_Exlab Startup_
Development of the frontend part of a platform for artisans from concept to MVP. Layout, logic, API, architecture. Reporting in YouTrack. Team collaboration following the Scrum methodology.
*******
### Projects
* __CraftShare__
A website for artisans. Implemented functionality includes interaction with articles, user accounts, and other authors.
[More info](https://github.com/vsmrnw/CraftShare "Source code link")
* __Ping-Pong__
Implementation of the game "Ping-Pong" using JavaScript and the Canvas element to create a graphical interface.
[More info](https://codepen.io/Yana-Saa/pen/abXObLq "Source code link")