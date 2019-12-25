# CustomDatePicker
Android 自定义日期选择控件

参考了github项目https://github.com/liuwan1992/CustomDatePicker/tree/update_20181221

详细说明参考 [Android 好看的自定义滚动式日期选择控件](https://blog.csdn.net/liuwan1992/article/details/52701475#comments)

&nbsp;
展示的时间范围是由传入参数决定的，注意 CustomDatePicker 的最后两个参数，决定了日期选择的范围。


&nbsp;  
效果图：

<img src="https://raw.githubusercontent.com/liuwan1992/CustomDatePicker/update_20181221/CustomDatePicker1.png" width = 30% height = 30% />&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/liuwan1992/CustomDatePicker/update_20181221/CustomDatePicker2.png" width = 30% height = 30% />

使用方法：

```
dependencies {
	 implementation 'com.github.CoderGxw:TimePicker:1.02'
	        }
```


```
<com.liuwan.demo.TimePicker
        android:id="@+id/time_picker"
        android:layout_width="300dp"
        android:layout_height="100dp"
        android:gravity="center_vertical"
        app:textColor="@color/selected_time_text"
        app:textSize="15sp"
        app:TimeRangeStart="2019-01-01 00:00"
        app:TimeRangeEnd="2020-01-01 00:00"/>
  ```
TimeRangeStart:可选时间的起始范围
TimeRangeEnd:可选时间的结束范围
