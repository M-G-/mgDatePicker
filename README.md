# mgDatePicker jQuery日期选择插件

## 使用

1.给输入框添加data-datepicker属性
```
<input type="text" data-datepicker />
```
2.页面加载时，创建日期选择器对象
```
new mgDatePicker()
```

## 配置

#### 1.位移

	日期选择器默认出现在对话框下面，如要修改位置，请添加[top]、[left]属性，单位为px。

举例：
```
<input type="text" data-datepicker="top:-33,left:254" />
```

#### 2.限制时间范围
	默认对选择日期范围无限制，如需限制范围，请添加[from]、[to]属性，接受形如“2016-6-6”表示日期的字符串，或“now”关键字表示今天。

举例：
```
<input type="text" data-datepicker="from:2016-6-4,to:now" />
```

#### 3.类型
	日期选择器默认只能选择日期，如需要选择时间，请添加type属性。
	
* type: date 选择日期，默认
* type: time 选择时间
* type: date-time 选择时间和日期

举例：
```
<input type="text" data-datepicker="type:date-time" />
```

	
