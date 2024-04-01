# Daria Nemirich

### Contacts

**Location:** Frankfurt am Main, Germany\
**Discord (rs school server):** Daria Nemirich (@dnemirich)\
[LinkedIn](https://www.linkedin.com/in/daria-nemirich-718a93233/)


---
### About me
Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое)

---
### Skills
Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)

---
### Code example

An example of code from codewars.com, task ["Mumbling"](https://www.codewars.com/kata/5667e8f4e3f572a8f2000039).
Function accum takes a string consisting only of letters from a..z and A..Z and converts it into such a string, that each character repeats the number of times that corresponds to the character's position in the string. Repetitions always start with a capital letter and are separated with a single dash.

**Examples:**\
accum("abcd") -> "A-Bb-Ccc-Dddd"\
accum("RqaEzty") -> "R-Qq-Aaa-Eeee-Zzzzz-Tttttt-Yyyyyyy"\
accum("cwAt") -> "C-Ww-Aaa-Tttt"

``` js
function accum(s) {
  const arr = s.toLowerCase().split('');
  let answer = [];
  for (let i = 0; i < arr.length; i++) {
    let counter = i + 1;
    let str = "";
    str += arr[i].toUpperCase();
    while (counter > 0){
      if (counter !== 1) {
        str += arr[i];
        counter--;
      } 
      else {
        answer.push(str);
        break;
      }
    }
   
}
  return answer.join('-');
}
```

---
### Job experience 
Опыт работы. Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код.

---
### Education

_2018 - 2020_  | M.Sc in Applied Mathematics and Informatics \
**ITMO University** (Saint Petersburg, Russia)

_2013 - 2017_  | B.Sc. in Biology \
**Saint Petersburg State University** (Saint Petersburg, Russia)

#### Additional Education:
_06.2024 - Present_   | 'RS School', Frontend-development\
_05.2021 - 01.2022_   | 'IT Girls School', Frontend-development\
_12.2018 – 01.2019_ | 'Machine learning’ online-course, Coursera

---
### Languages

- English (Upper-Intermediate)
- German (Intermediate)
- Russian (Native)
