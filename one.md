# 标题1
## 标题2
### 标题3
<p id="1"> <p>

*斜体*<br>
**粗体**

***粗斜体***

>引用

代码引入
	//入栈
	
	status push(sqstack &s,selemtype &e){
    if(s.top-s.base>=s.stacksize){
    	s.base = (selemtype *)realloc(s.base,(s.stacksize+stackincre)*sizeof (selemtype));
		if(!s.base)exit(overflow);
		s.top=s.base+s.stacksize;
		s.stacksize+=stackincre; 
    }	
    *s.top++=e;
    return ok;
	} 
	
```C++
//入栈
status push(sqstack &s,selemtype &e){
    if(s.top-s.base>=s.stacksize){
    	s.base = (selemtype *)realloc(s.base,(s.stacksize+stackincre)*sizeof (selemtype));
		if(!s.base)exit(overflow);
		s.top=s.base+s.stacksize;
		s.stacksize+=stackincre; 
    }	
    *s.top++=e;
    return ok;
} 
```
`另外一种`

[链接。百度的名称](www.baidui.com)

<a href="#1">HTML标签在这里可以用，调到开始<a>

|开|si|表|
|:---|:--:|--:|
|1111|222|333|
|111|2222|333|
|111|222|3333|
|111|222|333|

