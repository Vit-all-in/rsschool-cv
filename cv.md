# rsschool-cv

## Bulatkin Vitaly

![This is an image](https://vit-all-in.github.io/img/1.png)

### Contacts 

1. Phone: +7 968 5339084
2. E-mail: bulatkin.vitalik@mail.ru
3. Telegram: @VitalBul 
4. Discord: Vital(@Vit-all-in)

### About me

I have analytical thinking and a desire for development.
I am interested in new projects and technologies for the possibility of growth, I am happy to solve various problems.

### Skills

- HTML
- CSS
- JavaScript (Basic)
- VS Code
- Figma
- Git

### Code example

Length of missing array

```
function getLengthOfMissingArray(arrayOfArrays) {
  const lengths = (arrayOfArrays || [])
    .map(a => a ? a.length : 0)
    .sort((a, b) => a - b)
  
  if (lengths.includes(0)) {
    return 0
  }

  for (let i = 0; i < lengths.length - 1; i++) {
    if (lengths[i] + 1 !== lengths[i + 1]) {
      return lengths[i] + 1
    }
  }

  return 0
} 
```
### Work experience

I have little experience in JS and Frontend development. I have worked on several small projects and am currently working on it.

### Education and courses

- JS, CSS, HTML video courses on YouTube
- JavaScript https://learn.javascript.ru/
- MDN https://developer.mozilla.org/

