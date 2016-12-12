CSS 外边距属性（Margin）   
	margin             		         在一个声明中设置所有外边距属性。
	</br>
	margin:10px;     		           上下左右外边距都为10px
	</br>
	margin:10px 20px;   		       上下外边距为10px 左右外边距20px      （如果要设置左右居中值为auto）
	</br>
	margin:10px 20px 30px;  	     上外边距为10px 左右外边距20px         下外边距30px
	</br>
	margin:10px 20px 30px 40px;  	 上外边距为10px 右外边距20px           下外边距30px 左外边距40px
	</br>
 	margin-bottom     		         设置元素的下外边距。    
	</br>
	margin-left     		           设置元素的左外边距。     
	</br>
	margin-right     		           设置元素的右外边距。     
	</br>
	margin-top     			           设置元素的上外边距。
	</br>
        
CSS 内边距属性（Padding）   
</br>
	padding     			             在一个声明中设置所有内边距属性。 
	</br>
	padding:10px;     		         上下左右外边距都为10px
	</br>
	padding:10px 20px;   		       上下内边距为10px 左右内边距20px   
	</br>
	padding:10px 20px 30px;  	     上内边距为10px 左右内边距20px          下内边距30px
	</br>
	padding:10px 20px 30px 40px;   上内边距为10px 右内边距20px            下外内距30px 左内边距40px    
	</br>
	padding-bottom    	 	         设置元素的下内边距。     
	</br>
	padding-left     		           设置元素的左内边距。    
	</br>
 	padding-right     		         设置元素的右内边距。     
	</br>
	padding-top     		           设置元素的上内边距。 
	</br>

background   
</br>
	background-attachment     	   设置背景图像是否固定或者随着页面的其余部分滚动。 scroll  fixed  inherit
	</br>
	background-color     		       设置元素的背景颜色。
	</br>
 	background-image     		       设置元素的背景图像。      
	</br>
	background-position     	     设置背景图像的开始位置。第一个水平 第二个垂直   
	</br>
	background-repeat    	 	       设置是否及如何重复背景图像。repeat no-repeat repeat-x repeat-y
	</br>
	background-size			           设置图片大小 可跟值一个或者两个   第一个值水平 第二个值垂直（px,%,cover,contain）
	</br>


color : #999999;                 文字颜色
</br>

font-family :                    宋体,
</br>
sans-serif;                      文字字体
</br>

font-size : 9px;                 文字大小
</br>
font-style:itelic;               文字斜体
</br>
font-variant                     设置小型大写字母的字体显示文本small-caps; /*小字体*/
</br>
letter-spacing : 1pt;            字间距离
</br>
line-height : 200%;              设置行高 
</br>
font-weight:bold;                文字粗体
</br>
text-decoration 文本是否下划线	 line-through 加删除线; overline 加顶线;underline 加下划线;none 删除链接下划线;
</br>
text-transform 控制文本的大小写	capitalize 首字大写;uppercase 英文大写;lowercase 英文小写;
</br>
text-align文本对齐方式right 文字右对齐;left 文字左对齐;center 文字居中对齐;justify 文字分散对齐
</br>
vertical-align设置元素的垂直对齐方式	top垂直向上对齐;bottom 垂直向下对齐;middle 垂直居中对齐;text-top文字垂直向上对齐;text-bottom文字垂直</br>
向下对齐

</br>
CSS 列表属性（List）   
</br>
	list-style             	      在一个声明中设置所有的列表属性。
	</br>
	list-style-image     	        将图象设置为列表项标记。   
	</br>
	list-style-position    	      设置列表项标记的放置位置。
	</br>
	list-style-type     	        设置列表项标记的类型。
	</br>
元素定位
</br>
	position		                 确定元素的位置
	</br>
	position:static 	           默认值；
	</br>
	position:fixed;	 固定定位（脱离文档流，把元素固定到浏览器窗口上，默认参照物浏览器窗口）坐标值：left、top、right、bottom
	</br>
	position:relative; 相对定位（不脱离文档流，元素相对自身的位置）坐标值：left、top、right、bottom
	</br>
	position:absolute;绝对定位（脱离文档流，元素在文档中的位置，默认是body,可设置参照物，把参照物设置为相对定位元素，一般以父元素或者直系元素）
</br>
边框线
</br>
	border:1px solid red;			  第一个值边框线粗细 第二个值边框线类型 第三个值边框线颜色
	</br>
	border-bottom:1px solid red;下边框线
	</br>
	border-left:1px solid red;	左边框线
	</br>
	border-right:1px solid red;	右边框线
	</br>
	border-top:1px solid red;		上边框线
	</br>
	border-width				        规定边框的宽度
	</br>
	border-style				        规定边框的样式  dotted点状线 dashed虚线 solid实线 double双线
	</br>
	border-color				规定边框颜色
	</br>
