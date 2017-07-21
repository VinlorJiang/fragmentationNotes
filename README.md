# fragmentationNotes
零碎的笔记记录



## 1.常用函数
### 1.1 fabs、fabsf、abs、fabsl：
    int abs(int); //处理int类型的绝对值
    float fabsf(float); //处理float类型的绝对值
    double fabs(double); //处理double类型的绝对值
    long double fabsl(long double); //处理long double类型的绝对值
### 1.2 floor取整函数，
    如：floor(1.2) = 1
 
## 2. iOS UITextField中复制和粘贴为中文：
    在plist里面Localization native development region 选择 china ，然后Localized resources can be mixed 选 YES，如果没有Localized resources can be mixed，需手动添加。另外需要注意系统设置的语言应为中文
