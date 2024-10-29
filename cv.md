# Yaraslava Panamarova

## Contacts
[Github](https://github.com/Gordislava)

[LinkedIn](https://www.linkedin.com/in/yaraslava-panamarova/)

---

## About
Frontend developer with experience working with the Vue framework
---

## Skills
* HTML
* CSS
* Javascript
---

## Code Examples

```
function proofread(str) { 
    let upperStr = str.toUpperCase();

    let strArr = upperStr.replace(/IE/g, 'EI').match(/[^.]+\.\s*|[^.]+$/g);

    if (!strArr) {
        let newIfStr = [];
        
        let ifString = upperStr.replace(/IE/g, 'EI');
        let start = ifString.slice(0, 1);
        let end = ifString.toLowerCase().slice(1);
        newIfStr.push(start + end);
        
        return newIfStr.join('');
    }


    let newStr = [];


    for (let i = 0; i < strArr.length; i++) {
        let start = strArr[i].slice(0, 1); 
        let end = strArr[i].toLowerCase().slice(1); 

        newStr.push(start + end.trimEnd());
    }


    return newStr.join(' ');
}
```

---

## Languages

* Russian
* English