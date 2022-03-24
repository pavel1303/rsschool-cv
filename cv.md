# LEBEDEV PAVEL
## Junior Frontend Developer
----------------------------
### My Contact Info 

* **Address**: Moscow | Stupino
* **Phone**: 8-926-378-79-01
* **E-mail**: lebedpavel.dev@gmail.com
* **GitHub**: [pavel1303](https://github.com/pavel1303)
* **Codewars**: [pavel1303](https://www.codewars.com/users/pavel1303)
* **Telegram**: [jonybravo13](https://t.me/jonybravo13) 
-----------------------------
### About Me

   I worked in the restaurant business for a long time, going from a line presence to a managerial position,
but decided to change the field of activity, as my work ceased to bring me pleasure.
I have been interested in the field of technology for a long time, and decided to start studying with Front-end development, as it combines creativity and programming, and allows you to create something new for the end user.
I have been studying development for a year now, I recently completed Stage 0 from RS Shcool, and of course I continue to study.

-----------------------------
### Skills
* HTML
* CSS
* JavaScript
* Git,GitHub
* VS Code
* Figma
-----------------------------
### Code examples
[RGB To Hex Conversion](https://www.codewars.com/kata/513e08acc600c94f01000001) 
```
function rgb(r, g, b){
  return `${decToHex(r)}${decToHex(g)}${decToHex(b)}`
}

function decToHex(num){
  let res = [];
  if(num <= 0){
    return '00'
  } else if(num >= 255){
    return 'FF'
  } else {
    let alphabet = '0123456789ABCDEF';
    while(num){
    res.unshift(alphabet[num % 16]);
    num = Math.floor(num / 16);
  }
  }
  return res.join('').length === 2 ? res.join('') : `0${res.join('')}`;
}
```
-----------------------------
### Education
* **University**: Russian New University, Finance and credit
* **Courses**: RS School Stage 0, RS School Stage 1(in progress)
* **Books**: Head First O’Reilly Learning JavaScript Programming, The Modern JavaScript Tutorial
-----------------------------
### Language 
* English: A2 Pre-Intermediate