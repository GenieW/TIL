## for(key in `배열/객체`)

- 배열

```sh
  const testArr = ["rk", "sk", "ek"];
  for(key in testArr) {
    console.log(key, testArr[key]);
  }
```

<img src="/img/javascript/for_in_array.png"> </img>

- 객체

```sh
  const testObj = {"rk":"가", "sk":"나", "ek":"다"};
  for(key in testObj) {
    console.log(key, testObj[key]);
  }
```

<img src="/img/javascript/for_in_object.png"> </img>

---

## forEach

```sh
  const testArr = ["rk", "sk", "ek"];
  testArr.forEach(element => console.log(element));
```

<img src="/img/javascript/forEach.png"> </img>

---

## filter

```sh
  var testArr = ["rk", "sk", "ek"];

  var result = [];
  result = testArr.filter( x => { return x !== "rk" });

  console.log(result);
```

<img src="/img/javascript/filter.png"> </img>
