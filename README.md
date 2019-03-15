# Collection of useful regular expressions

## Matches every character between to strings

```js
(STRING)(.*[\s\S]+?)(STRING)
```

## Matches every character apart from numbers

```js
/[^0-9.]/g
```
