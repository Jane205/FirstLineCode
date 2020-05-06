## 变量和常量
### 声明和赋值

```
// 变量声明赋值
var a: Int = 2
var b = "hello world"

// 常量声明赋值
val c = 0L
val d: Boolean = false
```
kotlin可以不用声明变量类型，直接赋值后会自动推断变量类型
修饰符val和var：  
var可以记为variable的缩写，意为可变的，var修饰的为可变变量  
val则可以记为var final的结合，意为不可变量，也就是常量，被val修饰的量赋值后不可以修改其值

## 函数
```
// 无返回值的函数,后面Unit可省略
fun eat():Unit{
	println("so delisious")
}

// 返回值为String的函数
fun say(): String {
    return "hello"
}

// 带参数和返回值的函数
fun sum(a:Int,b:Int):Int {
	return a + b
}
// 上述可简写为
fun sum(a:Int, b:Int) = a + b

// 进一步，参数可以指定默认值 调用 sum(1) => 11; sum(2,3) => 5
fun sum(a:Int, b:Int = 10) = a + b
```
## 类和对象（class & object）
类：抽象的模板，如人类，车，学生，猫等  
对象：具体的个体，如你，我，你的特斯拉，李雷，韩梅梅，加菲猫等
以人类和人个体为例：


### 类 class


### 通过类生成对象
