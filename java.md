5.29
##### 标准框架
package com.imooc;//包名</br>
public class HelloWorld {</br>
    public static void main(String[ ] args) {</br>
    //代码内容</br>
    	}</br>
}</br>

##### Scanner工具类获取用户输入的数据
###### 步骤</br>
1. 位于 java.util 包中，使用前先导入java.util.Scanner
1. 创建 Scanner 对象
1. 接收并保存用户输入的值
###### 代码
package com.imooc;  //包名</br>
import java.util.Scanner;  //导入java.util包 </br>
public class HelloWorld {</br>
    public static void main(String[ ] args) {</br>
    Scanner input = new Scanner(System.in);  </br>
    // 创建Scanner 对象； input为对象的名字，并不固定；因为接收的是int型变量所以是System.in(相关内容见下方)</br> 
    int x = input.nextInt();//获取用户的输入，并保存在x；因为是int类型所以是 input.nextInt();（相关内容见下方） </br>
    //代码内容</br>
    	}</br>
}</br>
