## CSS 20

# Flexbox Defense

Wave 1

```
justify-content: center;

```

Wave 2

```
 .tower-group-1 {

    display: flex;
    justify-content: flex-end;

}
.tower-group-2 {

    display: flex;
    justify-content: center;

}
.tower-group-3 {

    display: flex;
    justify-content: flex-end;

}
```

Wave 3

```
 .tower-group-1 {

    display: flex;
    justify-content: center;

}
.tower-group-2 {

    display: flex;
    justify-content: space-between;

}
```

Wave 4

```
 .tower-group-1 {

    display: flex;
    align-items: flex-end;

}
.tower-group-2 {

    display: flex;
    align-items: flex-end;

}
```

Wave 5

```
 .tower-group-1 {

    display: flex;
    justify-content: space-around;
    align-items: flex-end;

}
.tower-group-2 {

    display: flex;
    justify-content: center;

}
.tower-group-3 {

    display: flex;
    align-items: center;
    justify-content: center;

}
```

Wave 6

```
 .tower-group-1 {

    display: flex;
    align-items: center;
    justify-content: space-between;

}
```

Wave 7

```
 .tower-group-1 {

    display: flex;
    flex-direction: column;

}
.tower-group-2 {

    display: flex;
    flex-direction: column;

}
```

Wave 8

```
 .tower-group-1 {

    display: flex;
    flex-direction: column;
    justify-content: space-between;

}
.tower-group-2 {

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;

}
```

Wave 9

```
 .tower-group-1 {

    display: flex;
    flex-direction: row-reverse;
    justify-content: space-around;

}
.tower-group-2 {

    display: flex;
    flex-direction: row-reverse;
    justify-content: space-around;
    align-items: center;

}
```

Wave 10

```
 .tower-group-1 {

    display: flex;
    justify-content: space-around;

}
.tower-1-1 {

}
.tower-1-2 {

    order: 2;

}
.tower-1-3 {

}
.tower-group-2 {

    display: flex;
    justify-content: space-around;

}
.tower-2-1 {

}
.tower-2-2 {

    order: -1;

}
.tower-2-3 {

}
```

Wave 11

```
 .tower-group-1 {

    display: flex;
    justify-content: space-between;

}
.tower-1-1 {

    align-self: flex-end;

}
.tower-1-2 {

}
.tower-1-3 {

    align-self: flex-end;

}
.tower-1-4 {

}
```

Wave 12

```
 .tower-group-1 {

    display: flex;
    justify-content: space-between;

}
.tower-1-1 {

    order: 1;

}
.tower-1-2 {

    align-self: center;
    order: 2;

}
.tower-1-3 {

    align-self: center;
    order: 4;

}
.tower-1-4 {

    align-self: center;
    order: 3;

}
.tower-1-5 {

    align-self: flex-end;
    order: 5;

}
```
