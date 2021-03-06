关于 Fecshop功能介绍
====================

Fecshop是一款电商系统，提供一下功能：

1.多Store，多语言，多域名，多货币，多模板。用户可以根据需要，添加[多个fecshop store](fecshop-feature-mutil-stores.md) ,
每个store设置不同的语言，[fecshop 多语言](fecshop-feature-mutil-stores.md),
每个store可以切换不同的货币，也就是 [Fecshop 多货币](fecshop-function-mutil-currency.md)
，同时，fecshop也支持[不同的store
设置不同的模板](fecshop-feature-mutil-themes.md)，

```php
支持不同Store使用不同的语言：譬如Store A 使用中文，Store B使用英文
		
支持不同Store使用不同的域名：譬如Store A 的域名为en.fecshop.com，Store B的域名为fr.fecshop.com
		
支持不同Store使用同一域名不同后缀：譬如Store A 的根路径为demo.fecshop.com/en， Store B的域名为demo.fecshop.com/fr
		
支持不同Store使用不同的货币：譬如Store A 使用的默认货币为英镑， Store B的默认货币为美元，当然，每个store都可以进行货币的切换
```

2.缓存功能

```php
全页缓存：在controller层面对整个页面进行缓存，动态数据通过ajax加载，提高网站的并发量。
		
block缓存：每个独立功能块都有Block缓存的功能，可以通过配置的方式设置缓存。
```
3.SEO


4.单例模式服务组件

```php
功能由底层 服务组件层 提供， 每一个组件以及子组件都是单例模式，只有在使用的时候才会被创建，创建之后不会再次创建，在系统中可以全局使用，您可以在任何一个地方初始化组件，设置组件，使用组件的功能，组件就像您的工具箱，可以在模块中的任何一个地方设置 services对象的参数，调取组件的功能数据。
```

5.Url自定义功能

```php
文章，产品，分类，博客等url，可以通过自定义的方式，定义自己想要的url，譬如定义分类的url为：
http://demo.fecshop.com/fashion-handbag-women-html.  
通过自定义分类的url path为 /fashion-handbag-women-html，即可实现
```

6.后台自定义html静态块

```php
对于页面底部，首页，产品页面等一些静态的html块，可以通过后台来修改内容，通过
配置的方式添加到页面中
```

7.文章功能

```php
用户可以发布文章，用来做文字条款，关于我们，等等一些单页面的展示。
```

8.用户功能

```php
用户可以注册账号，登录网站，修改资料，密码，查看历史产品评论，历史订单，
产品收藏，编辑多货运地址等功能。
二期会加入网盟，积分，批发，线下等功能。
```

9.分类功能

```php
1.用户可以添加编辑删除分类以及子分类。
2.后台为分类添加产品。
3.分类按照销量，name，价格等排序
4.分类侧栏按照颜色，尺码，和其他的一些属性进行过滤产品。
5.为分类添加feature product。
6.支持多语言
7.可以为分类设置属性组，进来侧栏产品属性过滤
```


10.产品功能

```php
1.产品支持多语言，多货币
2.双模式支持，
模式一：sku和spu模式，客户需要为每一个spu产品下面的每一个sku进行编辑
这种模式的好处是，在分类侧栏可以很好进行属性的过滤，譬如不同的颜色过滤
出来同一spu对应的相应颜色的sku图片。
缺点就是：编辑产品比较繁琐。

模式二：通过custom option的方式。这种方式可以比较方面的添加产品
但是在搜索的时候，不能根据颜色加载出来相应的颜色对应的图片。
```


11.搜索功能

```php
1
```



12.购物车模块

```php
1
```


13.货运模块

```php
1
```

14.支付模块

```php
1
```

15.博客模块

```php
1
```

16.网盟模块

```php
1
```





















