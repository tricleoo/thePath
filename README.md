# thePath
[thePath](https://curtis-l.github.io/thePath/)是一个使用Echarts展示PT站官方邀请路线的页面

# 注意事项
- 如有错误或更新，欢迎提issue或pr
- 图中官方邀请可能更新不及时。
- 录入时可能存在各站名称不一致的情况。
- 图中彩色站点为已录入的站点
- 站点要求复杂时用others代替

# json数据结构
数据分为data、links、site_list三部分
data为各个站点信息
```
 {
	"name": "***",  #名称
	"draggable": true,  #是否可拖拽
	"symbolSize": [50, 50],  #大小
	"itemStyle": {
		"color": "#000"  #颜色
		}
}
```
links为站点之间的关系
```
 {
	"target": "***",  #目标站点
	"source": "***",  #源站点
	"category": "",  #要求
}
```
site_list为站点列表

*将逐步开源生成thePath json文件的python代码*

# Telegram频道
https://t.me/theptpath
