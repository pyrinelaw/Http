## Http请求控件 ##

---

**使用**

```javascript
Http.get(url);                  // get请求
Http.post(url, data);           // post请求
Http.ajax(method, url, data);   // get、post综合
```


**示例**

```javascript
var request = Http.post("test.php", {k1: v1, k2: v2});
request.onData = function(response){
   // Success !!! Do something
}
request.onError = function(error){
   // Error !!! Do something
}
```


**Demo:** [http://pyrinelaw.github.io/Http](http://pyrinelaw.github.io/Http)

**Download:** [https://www.github.com/pyrinelaw/Http](https://www.github.com/pyrinelaw/Http)



