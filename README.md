fekey-preprocessor-extlang
===========================

fekey preproccessor plugin for parse swig custom tags.

支持使用Swig script, style 插件的JavaScript的语言扩展

```tpl
{% script %}
    require('./a.js');
    __inline('./b.js');
    var a = __uri('./c.js');
    //blabla
{% endscript %}

{% style %}
@import url(./a.css?__inline);
{% endstyle %}
```

