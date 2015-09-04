# 我的笔记
+ display: inline-block。IE6、IE7下可以通过display:inline,zoom:1来模拟。
+ display: table。IE6、IE7下可以通过&lg;table&gt;来做兼容。
+ display: flex。flex-item宽度会根据内容自适应。高度会默认拉伸与父容器同高，通过align-items属性来改变。IE6、IE7、IE8不支持~
+ display: table-cell。table-cell可以设置vertical-align属性。