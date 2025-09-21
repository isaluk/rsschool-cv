# Irina Saluk

---

## Contacts:
__📍 Location:__ Buenos-Aires | __📧 Email:__ [salukwork@gmail.com](mailto:salukwork@gmail.com) | __📞 Phone:__ +54 (911) 3298142*

---

## About Me 

### Junior Frontend Developer | Email & Landing Page Specialist

After earning a degree in accounting in 2018, I realized my passion lay in IT. This led me to pursue a second higher education in software engineering at Gomel State Technical University named after P.O. Sukhoi. While my part-time studies limited hands-on programming experience, I proactively self-taught:

* Email template and landing page development,
* Core HTML/CSS and JavaScript,
* Tools for building responsive designs.

Currently, I’m advancing my skills through the __RS School__ course to transition into commercial frontend development. I thrive on challenges, rapid learning, and collaborative environments.

__Goal:__ Join an IT company where I can apply my current skills while growing as a frontend developer.

---

## Skills

### Frontend Development

* HTML5 (semantic markup, accessibility)
* Pug (Jade) – templating engine
* CSS3 (Flexbox, Grid, animations)
* LESS (variables, mixins, nesting)
* JavaScript (ES6+ basics, DOM manipulation)

### Design & Prototyping

* Adobe Photoshop (basic image editing)
* Figma (UI design, prototyping, components)
* Version Control
* Git (basic commands)

### Workflow

* Responsive design principles
* Cross-browser compatibility
* Email template development

---
## Code Example

### Email Button with MSO Fallback
_Ensures proper rendering in Outlook (Microsoft Office) while maintaining modern email client compatibility._

```
<div>
  <!--[if mso]>
    <v:roundrect 
      xmlns:v="urn:schemas-microsoft-com:vml" 
      xmlns:w="urn:schemas-microsoft-com:office:word" 
      href="http://example.com" 
      style="height:40px;v-text-anchor:middle;width:200px;" 
      arcsize="25%" 
      stroke="f" 
      fillcolor="#087bf7">
      <w:anchorlock/>
      <center>
  <![endif]-->
  
  <a href="http://example.com"
     style="background-color:#087bf7;
            border-radius:10px;
            color:#ffffff;
            display:inline-block;
            font-family:sans-serif;
            font-size:13px;
            font-weight:bold;
            line-height:40px;
            text-align:center;
            text-decoration:none;
            width:200px;
            -webkit-text-size-adjust:none;">
    Super button!
  </a>
  
  <!--[if mso]>
    </center>
    </v:roundrect>
  <![endif]-->
</div>
```

> [!NOTE]
>  __Key Technical Notes:__
>  1. __MSO Conditional Comments__ – Targets Microsoft Outlook specifically
>  2. __VML (Vector Markup Language)__ – Required for rounded corners in Outlook
>  3. __Mobile Optimization__ – Inline styles and -webkit-text-size-adjust prevent iOS sizing issues
>  4. __Fallback Structure__ – Modern clients see the standard `<a>` tag while Outlook renders the VML version

---
## Education

__Gomel State Technical University named after P.O. Sukhoi__ <br>
*2018–2020* | Faculty of Automated and Information Systems <br> 
__Information Systems and Technologies__ (Second Higher Education)

* Part-time (correspondence) program while exploring tech career paths

__Belarusian State Agricultural Academy__ <br>
*2014–2018* | Faculty of Accounting <br>
__Accounting, Analysis and Audit__ (Specialist Diploma)

---

## Languages

* __Russian:__ Native
* __English:__ Basic (A1)