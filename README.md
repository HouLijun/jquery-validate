# Jquery-Validate
[http://www.runoob.com/jquery/jquery-plugin-validate.html](http://www.runoob.com/jquery/jquery-plugin-validate.html);
### jquery.validate.js
```javascript
$.extend( $.validator, {
    defaults: {
        messages: {},
        groups: {},
        rules: {},
        errorClass: "error",    //验证错误的类名
        validClass: "valid",    //验证通过的类名
        errorElement: "label",  //验证错误添加的元素
        focusCleanup: false,
        focusInvalid: true,
        errorContainer: $( [] ),
        errorLabelContainer: $( [] ),
        onsubmit: true,
        ignore: ":hidden",
        ignoreTitle: false,
    }
});
```