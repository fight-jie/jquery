(function(window, undefined) {
  变量定义赋值
  jquery.fn = jQuery.prototype = {
    jquery:
    constructor:
    init: f
    selector:
    length:
    toArray: f
    get: f
    pushStack: f
    each: f
    ready: f
    slice: f
    first: f
    last: f
    eq: f
    map: f
    end: f
    push:
    sort:
    splice:
  };
  jQuery.fn.init.prototype = jQuery.fn;
  <!-- 扩展函数的定义 -->
  jQuery.extend = jQuery.fn.extend = function() {

  }
  <!-- 扩展函数调用 -->
  jQuery.extend({
    这里的函数方法没有完全暴露到外面，部分不可用，仅供jquery.js调用
  })
})(window)