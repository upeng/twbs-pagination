## jQuery pagination plugin (bootstrap powered) ##
## jQury分页插件（支持bootstrap）## 
### Basic usage ###
### 基本使用方法 ###
Plugin requires jQuery (required - 1.7.0 or higher).
You can use Bootstrap CSS styles and markup (or use your own). 
The following code shows call the function on `<ul>` tag (it can be also `<div>` tag).

> 插件基于jQuery（要求jQuery版本>=1.7.0），你可以使用bootstrap css样式和标记（也可以使用你自己定义的样式）
下面的示例代码展示调用该插件的函数twbsPagination，选择器#pagination-demo可以是ul标记也可以是div等等
```javascript
$('#pagination-demo').twbsPagination({
  totalPages: 35,
  visiblePages: 7,
  onPageClick: function (event, page) {
    $('#page-content').text('Page ' + page);
  }
});
```

For more information see [docs on github pages](http://esimakin.github.io/twbs-pagination/) 