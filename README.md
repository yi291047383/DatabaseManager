# Android本地数据库管理

##结合ormlite，实现本地数据库结构的自动升级。
###当数据库表有变化时（包括增加表或者已有表列的变化），无需添加任何升级相关的代码，只需增加数据库版本号即可。当然，如果需要自定义表结构升级逻辑，也可重写默认的升级方案。
##结合Rxjava，实现数据的异步读写操作。
###通过异步读写，避免数据库操作对界面造成的卡顿
###使用LruCache缓存查询结果，避免不必要的数据库IO操作，加快数据查询效率。

