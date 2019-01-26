### pathjs
---
https://github.com/mtrpcic/pathjs

```js
function clearPanel(){
}
Path.map("#/users").to(function(){
  alert("Users!");
});
Path.map().to(function(){
  alert("Comments!");
}).enter(clearPanel);
Path.map("#/posts").to(function(){
  alert("Posts!");
}).enter(clearPanel);
Path.root("#/posts");
Path.listen();
```

```
```

```
```

