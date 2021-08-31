reserved word ：goto const
identifier ：every word and $ or 0-9, except reserved word and key word
no limitide of length but the first character must not number and can not use space in identifier 
1、标识符用作给变量、方法和类命名。

2、以字母、下划线“_”和“$”符开头，后面可跟字母、下划线“_”和“$”符或数字。

3、大小写敏感。

4、应该使用有意义的名称，达到见名知意的目的，并且长度无限制。

5、尽量不要使用中文。

6、不可以是true和false。true和false虽然不是关键字，但是有特殊用途。

7、避免与java关键字与java类库的类名重名，java关键字一共有51个，如下：

二、对于不同标识符使用不同的命名规则

1、包名：全部小写，用”.”隔开，每一个点表示一级目录，至少要有一级目录。

(1) 单级包：小写。如：com

(2) 多级包：小写，用”.”隔开。如：com.baidu.www

2、类或接口：所有单词首字母大写。(大驼峰法)

(1) 一个单词：首字母大写。如：Student、People

(2) 多个单词：每个单词首字母大写。如：HelloWorld、ServerSocket

3、方法或变量：第一个单词首字母小写，从第二个单词开始首字母大写。(小驼峰法)

(1) 一个单词：首字母小写。如：name、age

(2) 多个单词：第二个单词首字母大写。如：stuName、showTime

4、常量：全部大写，单词键以下划线”_”隔开

(1) 一个单词：全大写。如：PI、COUNT

(2) 多个单词：全大写，并以”_”隔开。如：RESULT_OK、WINDOW_HIERARCHY_TAG

总之，遵循这个命名规范，不止有利于别人能够更快速的读懂我们的代码，了解代码中的成员，还能够让我们在实际开发中减少很多不必要的麻烦。
见名知意

package name : xxxyyyzzz 
class name : XxxYyyZzz
variable name;multiword :xxxYyyZzz
constant name:XXX_YYY_ZZZ

varibale : int float 

1.变量的使用 变量的格式 数据类型 变量名 = 变量值；
2.变量必须先声明，后去使用；
	变量都在其作用域内有效
	同一个域内不能定义两个同名变量


		class VariableTest {
			public static void  main(string [] arags){
			int myAge = 12;
			System.out.printlm(myAge);
			}
		}


java data type
classify by data type
	primitive type : char\boolean
		number type : byte\short\int\long\float\double
	reference type: class\interface\[]
	
	基本数据类型：
		整形：byte(1bype)、short(2bype)、int(4bype)、long(8bype)
		浮点型：float(4bype)(Single precision)、double(8byte)(double precision)
		字符型：char(1byte) useing 'a'
		布尔型：boolean
	饮用数据类型：
		类（class）
		接口（interface）
		数组（array）
	变量在类中声明的位置：
		成员变量 vs 局部变量
	

/*
class VariableTest1 {
public static void  main(string [] arags){
	/long type variable must end with "L" no matter of capital letters or a lowercase letter
	/float type variable must end with "F" no matter of capital letters or a lowercase letter 
	int myAge = 12;
	System.out.printlm(myAge);
	char c3 = 'b'
	//char type only one type
	}
}
*/


