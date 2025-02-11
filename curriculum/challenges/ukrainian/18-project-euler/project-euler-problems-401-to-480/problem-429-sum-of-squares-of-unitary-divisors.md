---
id: 5900f5191000cf542c51002c
title: 'Завдання 429: сума квадратів унітарних дільників'
challengeType: 1
forumTopicId: 302099
dashedName: problem-429-sum-of-squares-of-unitary-divisors
---

# --description--

Унітарний дільник $d$ числа $n$ — це дільник $n$, що має властивість $нсд(d, \frac{n}{d}) = 1$.

Унітарними дільниками $4! = 24$ є 1, 3, 8 та 24.

Сума їхніх квадратів дорівнює $12 + 32 + 82 + 242 = 650$.

Нехай $S(n)$ представляє суму квадратів унітарних дільників $n$. Таким чином, $S(4!) = 650$.

Знайдіть $S(100\\,000\\,000!)$ за модулем $1\\,000\\,000\\,009$.

# --hints--

`sumSquaresOfUnitaryDivisors()` має повернути `98792821`.

```js
assert.strictEqual(sumSquaresOfUnitaryDivisors(), 98792821);
```

# --seed--

## --seed-contents--

```js
function sumSquaresOfUnitaryDivisors() {

  return true;
}

sumSquaresOfUnitaryDivisors();
```

# --solutions--

```js
// solution required
```
