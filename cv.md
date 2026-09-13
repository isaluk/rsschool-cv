# Irina Saluk

**Junior Frontend Developer | HTML Email Developer**

**📍 Location:** Buenos-Aires | **📧 Email:** [salukwork@gmail.com](mailto:salukwork@gmail.com) | **Telegram:** [@i_saluk](https://t.me/i_saluk) | **📞 Phone:** +54 (911) 3298142\*

---

## About Me

I am a Junior Frontend Developer and HTML Email Specialist. After earning a degree in accounting in 2018, I realized my passion lay in IT, which led me to pursue a second degree in software engineering. I have practical experience in developing responsive HTML email templates and landing pages. Currently, I am advancing my modern frontend skills through the **RS School** course to transition into full-time commercial frontend development. I thrive on challenges and rapid learning in collaborative environments.

---

## Skills

### Frontend Development

- HTML5 (semantic markup, accessibility) and CSS3 (Flexbox, Grid, animations)
- JavaScript (ES6+ basics, DOM manipulation) and TypeScript
- Pug (Jade) and LESS
- Responsive Web Design and cross-browser compatibility
- Responsive HTML email templates and table-based layouts. Dark mode styling, email-safe CSS, and remote image hosting

### Tools & Workflow

- Git, GitHub, and VS Code
- Figma (UI design, prototyping) and Adobe Photoshop (basic image editing)
- Vite and Supabase (basics)

---

## Experience & Projects

### Freelance HTML Email & Frontend Developer (5+ years)

- Over 5 years of experience developing responsive HTML email templates and landing pages. [Portfolio](https://kwork.com/user/saluk_dev)

### DevQuest (RS School Project)

- Web application developed using TypeScript, Vite, and Supabase. Implemented authentication, protected routes, and game state management.
  [GitHub](https://github.com/OlgaMinaievaWebDev/rs-tandem-devquest)

---

## Code Example

### Codewars Kata: [Advanced Events](https://www.codewars.com/kata/52d4678038644497e900007c)

_My solution to a JavaScript algorithmic challenge on Codewars._

```javascript
function Event() {
  let events = [];
  this.subscribe = function (...args) {
    args.forEach((a) => {
      if (typeof a === "function") {
        events.push(a);
      }
    });
  };
  this.unsubscribe = function (...args) {
    args.forEach((a) => {
      if (typeof a === "function") {
        let ind = events.lastIndexOf(a);
        if (ind !== -1) {
          events.splice(ind, 1);
        }
      }
    });
  };
  this.emit = function (...args) {
    const n = [...events];
    n.forEach((a) => a.call(this, ...args));
  };
}
```

---

## Education

### RS School — JavaScript / Front-end Development

- _2025–2026_ | **[Certificate](https://app.rs.school/certificate/iz3v519l)**

### Gomel State Technical University named after P. O. Sukhoi

- _2018 – 2020_ | Faculty of Automated and Information Systems

- **Software Engineer** (Second Higher Education)

### Belarusian State Agricultural Academy

- _2014–2018_ | Faculty of Accounting

- **Accounting, Analysis and Audit** (Specialist Diploma)

---

## Languages

- **Russian:** Native
- **English:** A2. Regular conversational practice through living abroad and frequent international travel, using English for everyday communication.
