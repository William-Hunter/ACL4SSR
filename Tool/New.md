* https://raw.githubusercontent.com/leosam1995/My_ACL_Rules/master/banAD.acl
* @leosam1995
# 更新历史：

# 3.16
# 2017年3月16日00:01:08 81
	去重
	合并中国IP段
	完善百度、letv、金立手机
	添加UC浏览器广告过滤
	添加墨迹天气，增强sohu、sougou等
	添加大量广告联盟，屏蔽效果更好
	添加爱奇艺广告ip段
	添加起点 掌阅 书旗 app广告

* 3.08
* 2017年3月7日20:34:30 71
	添加推特 tumblr 增强youtube
	增强爱奇艺
	大范围改动 加强 去重
	
* 3.03
* 2017年3月3日21:06:39 65
	屏蔽大量广告联盟
	屏蔽小米MIUI和魅族flyme rom广告
	
* 3.02
* 2017年3月2日08:27:48 59
	屏蔽大量广告联盟
	精简运营商广告
	
* 3.01
* 2017年3月1日19:57:10 56
	添加运营商广告
	修正关键字拦截
	
* 2.18
* 2017年2月27日15:20:49 02.27
	日常优化
	添加直连
	拆分广告过滤规则，容易维护
	
* 2.13
* 2017年2月25日20:28:31 02.25
	日常优化
	
* 2.11
* 2017年2月23日19:33:13 02.23
	大范围精简直连列表
	添加深圳运营商ip
	
* 2.09
* 017年2月22日17:04:19 02.22
	添加运营商ip
	修善百度
	完善谷歌去广告
	
* 2.06
* 2017年2月19日08:07:30 02.19
	去重、排序！
	改善广告关键词
	改善ali广告等广告
	升级优酷广告拦截
	
* 2.05 ★★★
* 2017年2月18日12:55:42 02.18
	合并大陆ip地址，缩减近1700条规则
	删掉MP4吧广告
	update有道和sohu
	去重、排序！！！！
	感谢@nian0114
	
* 2.03
* 2017年2月17日16:34:01 02.17
	备注更明确
	删除重复规则
	修复高德不能更新问题
	修复国外域名正则匹配
	
* 2.01 ★★★
* 2017年2月17日10:40:44 02.17
	按字母排序
	大范围完善
	日常添加修改规则
	添加几个国内广告商和关键词
	
* 1.14
* 2017年2月15日19:45:36 02.15
	修复MytvSUPER & Netflix 和line软件
	添加喜马拉雅电台过滤
	添加部分规则
	
* 1.13
* 2017年2月15日13:13:20 02.15
	删除部分第三方规则
	添加广告关键词
	修复正则的\-问题
	
* 1.11
* 2017年2月14日12:00:06 02.14
	添加直连关键词
	修补规则
	解决google play无法更新问题 (^|\.)gvt1\.com$
	
* 1.08
* 2017年2月11日18:23:46 02.11
	添加芒果TV、风行、搜狐、qq、酷狗、酷我、京东广告过滤规则
	添加大量第三方广告拦截规则
	添加运营商广告
	删除Weifeng广告和apple直连站点--苹果的 安卓不用
	几乎重写规则 无重复规则
	
* 1.07
* 2017年2月11日09:49:47 02.11
	添加广告拦截关键词
	添加直连关键词
	添加直连域名
	
* 1.06
* 2017年2月7日15:39:05 02.7
	增加几个广告域名拦截关键字：admob qtmojo trace traffic
	增加几个直连网站域名关键词
	国外知名域名后缀直连：us tw jp等
	增加国外软件关键字 全部代理
	删除几个受影响的广告拦截网站
	
* 1.04 ★★
* 2017年2月5日15:12:56 02.05
	精简[proxy_list]列表
	删除* Top blocked sites列表 加快匹配速 [正则语法.conf](正则语法.conf) 度
	
* 1.03
* 2017年2月5日10:00:51 02.05
	将视频APP拦截规则分开 更清晰
	合并爱奇艺 优酷土豆 乐视TV 搜狐 PPTV 6.cn 视频app规则
	
* 1.02 ★★★
* 2017年2月4日23:21:17  02.04
	重要更新：（总体来说加快正则匹配速度） [正则语法.conf](正则语法.conf) 
	合并百度 网易 淘宝 的广告屏蔽
	
* 1.01 重大更新★★★
* 2017年2月4日14:17:50  02.04
	重要更新：（总体来说加快正则匹配速度）
	改写正则匹配规则，减少回溯，效率提高很多！！！！
	合并新浪 QQ 网页的广告屏蔽
	添加酷安直连
	
* 0.25
* 2017年2月3日11:48:59  02.03
	把AD规则进行去重 排序优化
	添加直连：唯品会 一号店 内涵段子 糗事百科
	精简 美图 Apple直连列表
	删除PlayStation Store广告和直连 安卓又不用 加他干啥呢
	删除*MytvSUPER & Netflix直连 安卓不用
	删除v2ex amazon代理里面的重复冲突
	
* 0.24
* 2017年2月2日11:56:31  02.02
	把greasyfork.org填加到直连列表（via浏览器
	
* 0.23
* 2017年1月31日20:39:12
	添加几个直连网站
	添加拦截联通运营商广告
	将美国.us域名加入代理并前置
	将中国3个特有域名加入直连:.中国.公司.网络 滑稽。。并无卵用
	
* 0.22
* 2017年1月30日18:16:28
	删减一些规则
	将禁止访问列表移动到前面 方便编辑
	
* 0.21
* 2017年1月30日17:49:46
	添加迅雷看看
	
* 0.20
* 2017年1月29日14:11:36
	添加国内直播、新闻、小说、文库等网站直连 大约20个
	
* 0.19
* 2017年1月29日12:59:43
	去重、排序！！！！
	添加org.cn、net.cn域名后缀直连
	
* 0.18
* 2017年1月28日21:00:34
	设置gov.cn、edu.cn和.cn域名直连
	添加拦截常用应用程序的隐私跟踪
	处理广告关键字：如有误伤，请见谅！
	如surge的DOMAIN-KEYWORD,admarvel,REJECT改成^(.*\.)?.*admarvel.*\..*$
	
* 0.17
* 2017年1月28日14:07:15
	去除Apple Mac规则 完善部分apple域名(安卓要啥苹果 滑稽)
	添加淘宝CDN 天猫 直连
	尝试修复本地localhost直连
	调整国内ip地址位置
	解决IT之家网页字体变小问题
	
* 0.16
* 2017年1月28日14:03:25
	更新优酷、爱奇艺
	更新完善 [运营商] 广告
	
* 0.16以前
* 2017年1月28日以前
	各种添加规则。。。。。
