# Profile UI - iKO

**iKO** is a clean and minimal profile UI built with *HTML*, *CSS*, and *JavaScript*. It features a user profile layout with an image, name, job title, follower/following stats, and interactive Follow and Message buttons. Users can also switch the site’s theme color with a single click.

[View Demo](https://developer-iko-mike.github.io/profile)

---

The JavaScript logic of this project is written in just a **single line!** :

```js
document.querySelectorAll('.color').forEach(color => color.addEventListener("click", e => document.documentElement.style.setProperty("--main", e.target.dataset.color)));
```