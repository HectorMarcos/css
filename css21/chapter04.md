# Chapter 4

```
crossbow {
  display: flex;
  align-items: center;
  justify-content: flex-end;
}
```

```
crossbow {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.target:nth-of-type(2) {
  align-self: flex-start;
}
```

```
crossbow {
  display: flex;
  justify-content: center;
  align-items: flex-end;
}

.target:nth-of-type(1) {
  align-self: stretch;
}
```

```
crossbow {
  display: flex;
  align-items: flex-start;
  flex-direction: row-reverse;
}

.target:nth-of-type(1) {
  align-self: center;
}
```

```
crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: flex-end;
  align-items: flex-start;
}

.target.male {
  align-self: flex-end;
}
```

```
crossbow {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.target:nth-of-type(2) {
  align-self: flex-end;
}
```

```
crossbow {
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
}

.target:nth-of-type(2) {
  align-self: stretch;
}
```

```
crossbow {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.target:nth-of-type(2) {
  align-self: flex-start;
}
```
