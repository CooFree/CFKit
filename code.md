

[货币API的封装 主要封装了加减乘除等等](https://github.com/tianya2416/WSubtractingCounter)

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
