

##### [货币API的封装 主要封装了加减乘除等等](https://github.com/tianya2416/WSubtractingCounter) 

```
typedef NS_ENUM (NSInteger, SubtractState) {
    NS_ENUM_Type_Add = 0,       //A+B       A+B = 18
    NS_ENUM_Type_Sub,           //A-B       A-B = 12
    NS_ENUM_Type_Mul,           //A*B		A*B = 45
    NS_ENUM_Type_Div,           //A/B       A/B = 5
    NS_ENUM_Type_Pow,           //A的3次方   A*A*A=
    NS_ENUM_Type_10Power        //A*10的3次方 A * 10*10*10
};

[WSubtractingCounter getCount:@"0" valueB:@"5" states:NS_ENUM_Type_Sub];
```

#####   [具有动画特效的UITabBar](https://github.com/LoongerTao/TLAnimationTabBar)

![](https://camo.githubusercontent.com/75db4d5b9ce8355029eb66f2daa3cb7328c82410/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333333333530302d336562326536653961656637353963362e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970)
