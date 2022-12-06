# rsschool-cv
---
## Natallia Patsiomkina
---
### Contact Info:
* **Phone:** +375 29 384-28-65
* **E-mail:** patsiomkina@inbox.ru
* **GitHub:** patsiomkina
---
### Briefly About Myself:
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.
---
### Skills and Proficiency:
* Python, PyTest, requests
* Selenium WebDriver
* Robot Framework
* Git, GitHub
* Bash
* SQL
* PostgreSQL
* HTML5, CSS3
* API, REST, SOAP, Postman, Soap UI
* QA, AQA
---
### Code example:
**Isograms from CODEWARS:** *An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.*
```
def is_isogram(string):
    new_str = ''
    for letter in string:
        new_str += letter
    new_set = set(new_str.lower())
    finish = ''.join(sorted(new_set))
    start = ''.join(sorted(string.lower()))
    if start == finish or string == '':
        return True
    else:
        return False
```
---
### Education:
* University: Francisk Skorina Gomel State University, Criminal Law and Procedure Major
* Courses:
    - FreeCodeCamp
    - HTML Academy
---
### Languages:
* **English** - Advanced (according to the online test at www.efset.org)
![English level test results](/media/sf_Learn_2022/WebstormProjects/rsschool-cv/English_level_test_results.png)
* **Russian** - Native
---
