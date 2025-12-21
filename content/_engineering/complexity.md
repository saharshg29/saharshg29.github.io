---
layout: post
title: "The Silent Cost of Technical Debt"
categories: Engineering
description: A reflection on why the fastest code isn't always the best code.
---
In software engineering, we often treat 'speed' as the primary metric. But after years of building, I’ve realized that maintainability is actually a form of empathy—for your future self and your teammates.

```javascript
// Simplicity > Cleverness
function calculate(v) {
  return v.map(i => i * 2); // Readable
}
```