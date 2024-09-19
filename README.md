# MMKVAndroidOnly

>  The original MMKV is here https://github.com/Tencent/MMKV.



## En

Sync with MMKV 1.3.9.

1. Projects update, update to gradle8.7+ for latest android Studio support.
2. Android15 16kb size changes NDK r27.

### How to compile?
1. git clone this project;
2. Set Build Variant to StaticCppRelease:

​    <img src=".\screenshot01.png" alt="screenshot01" style="zoom:80%;" />

3. Never mind the active ABI;
4. Click on "hammer" to compile and get aar here:   

<img src=".\screenshot02.png" alt="screenshot02" style="zoom:80%;" />

Window or Mac(arm) compiled successful.




## 中文

同步MMKV 1.3.9的代码。

1. 重新调整MMKV的工程以便适配gradle8.7+和最新的android Studio。
2. 调整c/c++代码适配android15 16kb size NDK r27。



### 怎么编译？

1. 克隆工程；
2. 设置Build Variant到StaticCppRelease；
3. 不用管Active ABI。

点击锤子进行编译即可。最后在mmkv模块下，build/outputs/aar/ 找到aar文件。

Window编译成功，arm版mac编译成功。
