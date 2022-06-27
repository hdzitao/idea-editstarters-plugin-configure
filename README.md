# idea-editstarters-plugin-configure
idea-editstarters-plugin 配置

* 鉴于重新解析spring-io/initializr的配置更加繁琐,采取比较笨的办法,有修改就再配置一个
* 依赖的增删不用新建一个,有添加就覆盖,删除不用管,总之取比较全面的那个,这部分由metadata的versionRange控制,不符合版本本来就会删除.