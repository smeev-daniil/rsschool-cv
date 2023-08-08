# DANIIL ZMEEV, JUNIOR DEVELOPER

![My profile picture](rsschool-cv/profile.jpg)

### Ways of contacting me:
* **email**: daniil.smeev@gmail.com
* **phone number**: +90(534)379-11-87
* **telegram**: @smeev_daniil
* **github**: smeev-daniil

## Brief info about me:
I am a novice front-end developer. Currently studying at _Leipzig University_, at the faculty of physics. **Spheres of interest**: radiation medicine, application of the Artificial Intelligence in radiation therapy, Data Science, front-end development.

## Hard skills:
* Git, GitHub
* Visual Studio Code
* Python, Pandas library
* HTML, CSS, JavaScript 
* Google services _as well as_ Microsoft Package

## Code example:
```
import re 

listik = []
with open('input.txt') as txt_file:
    for line in txt_file:
        listik.append(re.findall('\+\d{8,15}', line))
spisok = []
for element in listik:
    for i in range(len(element)):
        spisok.append(element[i])
spisok.sort()

with open('output.txt', 'w') as txt_file:
    for i in range(len(spisok)-1):
        print(spisok[i], end = ',', file = txt_file)
    print(spisok[len(spisok)-1], file = txt_file)
```

## Working experience:
* RS-School Front-end development course. [Project CV](https://github.com/smeev-daniil/rsschool-cv)

## Education:
* **Lomonosov Moscow State University** (Moscow, Russia), _Sept 2019 - July 2022_
* **Leipzig University** (Leipzig, Germany), _June 2023 - July 2024 (pending)_
### Additional education:
* **"Python for processing big sources of data" course** (Lomonosov Moscow State University, faculty of Cybernetics), _February 2022 - June 2022_
* **"Front-end development" course** (RS SCHOOL), _July 2023 - ..._

## Languages:
* Russian - mother language
* English - C1 (IELTS Academic 7.0)
* French - B1
* German - A2
* Turkish - A1