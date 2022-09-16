# Sergey Vashev

### Contact information:

**Phone:** +375335973525 \
**Email:** foxter6600@gmail.com \
**Vkontakte:** [Sergey Vashev](https://vk.com/id2265581) \
**Codewars:** [foxter6600](https://www.codewars.com/users/foxter6600)

### Briefly About Myself:

Having started my career in 2009 as an electrician servicing fire automatics, security and video surveillance systems at an enterprise whose activity related with pumping of oil and oil products. Two years later I was already leading a small team of seven people. After some time, I realized that there was no feeling of movement forward, that the current activity did not satisfy my needs of new knowlege - malfunctions of the equipment were being resolved quickly and easily, new types of equipment did not appear as often as I would like. Therefore, I turned my attention to web development, which offers almost limitless opportunities for improving skills. Now I am actively moving in this direction.

### Skills:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code

### Code example:

Find the unique number KATA from Codewars: There is an array with some numbers. All numbers are equal except for one. Try to find it!

```
function findUniq(arr) {
  const counter = arr.reduce((acc, item) => {
    acc[item] = acc[item] ? acc[item] + 1 : 1
    return acc
  }, {})
  const result = Object.keys(counter).filter((item) => counter[item] === 1)
  return Number(result[0])
}
```
