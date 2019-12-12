# translate
这是一个将中文网站翻译成英文的组件|it is a tool to translate your Chinses website--base on baidu-translate
![Image text](https://raw.githubusercontent.com/JJawesomeJJ/translate/master/usage.png)
js 使用：
var language=new zh_translate_en();
language.start('/language');
php 用法：
auto_load::load('translate.translate');//引入php文件的方法 我自己写的框架的导入方式 后端人员的自行导入
$translate=new translate("20191211000365022","7FNf18sNuFHbJvAJB0qg");
return $translate->translate($request->get("zh"));
            
