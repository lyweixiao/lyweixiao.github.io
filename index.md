数组的遍历方法及区别

.map
vue-resource相当于第三方包用于发送请求，获取数据。有三种方式，分别为get,post,jsonp,
通过调用接口地址(this.$http.get/post/jsonp)，然后.then(result => {
         console.log(result.body)
})
