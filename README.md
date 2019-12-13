# translate
这是一个将中文网站翻译成英文的组件|it is a tool to translate your Chinses website--base on baidu-translate
![Image text](https://raw.githubusercontent.com/JJawesomeJJ/translate/master/usage.png)
js 使用：
var language=new zh_translate_en();
language.start('/language');
php 用法：
auto_load::load('translate.translate');//引入php文件的方法 我自己写的框架的导入方式 后端人员的自行导入
$translate=new translate("app_id","secret_id");
return $translate->translate($request->get("zh"));
使用：
请在http://api.fanyi.baidu.com/ 
申请注册通用类型账号获取app_id 与secret_id在上述php文件中传入使用即可
@记得配置js请求的路由还在通用免费的账号每一秒只能有一个请求  后端人员记得加锁以防止在同一秒内的多个请求  百度翻译api将不予受理
            
