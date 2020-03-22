元类：一切都是源自于type这个元类
    class定义类其中的逻辑是用type定义了一个类，且赋予了属性和方法，方法本质上也是属性
    class Person(object):
        name = "jack"
        def eat(self):
            print("I am eating")
     等同于
     Person = type("Person",(object,),{"name":jack})
     def __init__(self,age):
        sele.age=age
        
