# `KeyedList` type
This is a simple package I've created to have a generalized keyed list, because I've been having trouble finding a different package that does this, oddly enough.

Demo:
```ts
const list: KeyedList<number> = {
    "hello": 0,
    "hi": 1
};

list["hola"] = 2;
```
