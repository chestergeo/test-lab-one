```
<picture>html
  <source media="(prefers-color-scheme: dark)" srcset="moon.png">
  <img alt="sun or moon, depends on theme" src="sun.png">
</picture>
```

renders as

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="moon.png">
  <img alt="sun or moon, depends on theme" src="sun.png">
</picture>

----

```html
<img alt="sun or moon, depends on theme" src="sun.png">
```

renders as

<img alt="sun or moon, depends on theme" src="sun.png">
