# crearfix
> clearfix css

```
.clearfix:before,
.clearfix:after {
  content: " ";
  display: table;
}
  
.clearfix:after {
  clear: both;
}
  
.clearfix {
  *zoom: 1;
}
```
