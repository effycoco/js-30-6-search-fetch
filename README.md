涉及到：

1. `fetch(url).then(response=>response.json()).then(data=>use(data))`;
2. string method: `replace`, `match`(接受正则表达式作为参数)
3. array method: `join`(将数组转换成 array), spread syntax, `filter`(回调函数需返回 true/false), `map`(对数组每个元素进行相同操作)
4. 利用正则表达式使数字变成带逗号的格式（🌟 常用）
5. `new RegExp(string,'gi')` g-global 表示查找所有符合的项，而非仅第一个，i-ignore case 表示忽略大小写
