<div align="right">
  <a href="README.md">
    <img alt="Ler em Portugês do Brasil" src="https://img.shields.io/static/v1?label=&message=Ler+em+Portugu%C3%AAs+do+Brasil&color=green&style=for-the-badge" />
  </a>
</div>

<table>
  <tr>
    <td><img src="https://i.ibb.co/SQDLQ19/first-to-last.png"></td>
    <td>  
      <h1>@desco/first-to-last</h1>
      NPM package that changes the N values from the beginning of the array to the end (or the other way around).
      <br /><br />
      <div align="center">
        <img alt="MIT License" src="https://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge">
        <img alt="Version 1.1.2" src="https://img.shields.io/static/v1?label=Version&message=1.1.2&color=blue&style=for-the-badge">
      </div>
      <h4 align="center"> 
        🚀 Ready to use! 🚀
      </h4>
    </td>
  </tr>
</table>

> <a href="https://github.com/desco-npm" target="_blank">See other NPM projects here.</a>

> <a href="https://github.com/descoifica" target="_blank">See other projects here.</a>

---

## 📋 Table of Contents

- [⚙️ Installation](#Installation)
- [📦 Import](#Import)
- [📚 How to use](#How-to-use)

---

<a name="Installation"></a>

## ⚙️ Installation

```bash
npm install --save @desco/first-to-last
```

> Note that it will be necessary to have **NPM** installed for the command to work.

---

<a name="Import"></a>

## 📦 Import

### Node

```js
const firstToLast = require("@desco/first-to-last");
```

### Browse

```js
import firstToLast from "@desco/first-to-last";
```

---

<a name="How-To-Use"></a>

## 📚 How to use

```js
const list = [1, 2, 3, 4, 5];
const obj = { a: 1, b: 2, c: 3, d: 4, e: 5 };

console.log(firstToLast(list, 2)); // [ 3, 4, 5, 1, 2, ]
console.log(firstToLast(obj, 4)); // { e: 5, a: 1, b: 2, c: 3, d: 4, }

console.log(firstToLast(list, 2, true)); // [ 4, 5, 1, 2, 3 ]
console.log(firstToLast(obj, 4, true)); // { b: 2, c: 3, d: 4, e: 5, a: 1 }
```

### Parameters

| Nome    | Tipo         | Padrão  | Descrição                                                       |
| ------- | ------------ | ------- | --------------------------------------------------------------- |
| list    | Array/Object | -       | List to be sorted                                               |
| count   | Number       | 1       | Number of items to be relocated                                 |
| reverse | Boolean      | `false` | If `true`, you will be redirected from the end to the beginning |

---

## Author

<table>
  <tr>
    <td width="150px">
      <img src="https://scontent.fsdu1-1.fna.fbcdn.net/v/t1.0-9/539886_235546170253505_5977326689811409130_n.jpg?_nc_cat=106&ccb=3&_nc_sid=174925&_nc_eui2=AeGgFWn_fWInwRkTo3mHSP993TbQ0TzG0Y3dNtDRPMbRjS-eZL1tr4I5maqz6O-jva9qWnIxKOsD3UtSm9CTeCys&_nc_ohc=Qw6NaDGrtIgAX9uFF2c&_nc_ht=scontent.fsdu1-1.fna&oh=5ebac9874d7a24e157c8c99fd965c2a4&oe=606539CE" width="100px;" alt=""/>
      <b>Rafael A. R. Dias</b>
    </td>
    <td>  
      <a href="mailto:eu@diasrafael.com.br" target="_blank" >
        <img alt="Email eu@diasrafael.com.br" src="https://img.shields.io/static/v1?label=Email&message=eu@diasrafael.com.br&color=red&logo=gmail&style=for-the-badge">
      </a>
      <a href="https://www.linkedin.com/in/diasrafael/" target="_blank">
        <img alt="Linkedin @diasrafael" src="https://img.shields.io/static/v1?label=Linkedin&message=@diasrafael&color=blue&logo=linkedin&style=for-the-badge">
      </a>
      <a href="https://www.facebook.com/eudiasrafael" target="_blank">
        <img alt="Facebook @eudiasrafael" src="https://img.shields.io/static/v1?label=Facebook&message=@eudiasrafael&color=blue&logo=facebook&style=for-the-badge">
      </a>
      <a href="https://github.com/descodifica" target="_blank">
        <img alt="GitHub Overview @descodifica" src="https://img.shields.io/static/v1?label=GitHub+Overview&message=@descodifica&color=black&logo=github&style=for-the-badge">
      </a>
      <a href="https://github.com/desco-npm" target="_blank">
        <img alt="GitHub NPM @desco-npm" src="https://img.shields.io/static/v1?label=GitHub+NPM&message=@desco-npm&color=black&logo=github&style=for-the-badge">
      </a>
      <a href="https://www.npmjs.com/org/desco" target="_blank">
        <img alt="NPM @desco" src="https://img.shields.io/static/v1?label=NPM&message=@desco&color=red&logo=npm&style=for-the-badge">
      </a>
    </td>
  </tr>
</table>
