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

  (function( window, undefined ) {
    <!-- Sizzle -->
  })(window)
})(window)

document.defaultView
  在浏览器中，document.defaultView 返回与文档关联的窗口对象，如果没有，则返回 null。This property is read-only. 在quirksmode模式下, IE 9 以下版本不支持 defaultView.