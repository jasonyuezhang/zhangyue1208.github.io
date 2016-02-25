---
title: ES2015 new features study note
updated: 2016-02-25 13:11
published: true
---

## Declarations
1. **let**: act like var without hoisting. Binding the declared variable with most closest parent scope.

```javascript
for (let i = 0; i < stories.length; i++) {
    publish(stories[i], function() {
        console.log(stories[i]);
    })
}
```

2. **const**:  