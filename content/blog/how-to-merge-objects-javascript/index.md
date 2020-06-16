---
title: How to merge two objects in JavaScript
date: '2020-06-15T13:28:00.000Z'
description: 'Learn how to create a new object that combines two objects properties'
---

Thanks to the introduction of the spread operator we can easily merge two objects into one in Javascript. Using the following method:

```javascript
const firstObject = {
  make: 'Land Rover',
  model: 'Discovery',
}

const secondObject = {
  color: 'Black',
}

const mergedObject = { ...firstObject, ...secondObject }
```

<br/>

Be careful when merging objects that share attribute names as the second will overwrite the first.
