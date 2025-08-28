# PNR 流程

1. AVH/TAOPEK/15APR

``` Text
AVH/城市对/日期
```


  ![image.png](https://tc-cdn.flowus.cn/oss/259c47a7-2963-4f03-a257-d9429b634bf5/image.png?time=1756368900&token=36590bd4cefb0bdce63c93e8f6ac46d3fc4fe936eb2ed5c9e2002f390e40a17e&role=free)

2. SD 预定座位

``` Text
格式 
>SD 1Y1

SD 序号仓位人数
```


3. NFD 最低票价查询

``` Text
NFD 城市对/航司

PAT:A
```


  ![image.png](https://tc-cdn.flowus.cn/oss/fc1c6e0a-69d4-4d25-a16f-93b9d6a3b35b/image.png?time=1756368900&token=199bd55c795388797775db5b161f72ad231a1f64ea4fe8fd46a0f2cb0ae5b4e7&role=free)

4. NM 姓名录入

``` Text
NM 1张三1李四
```


5. SSR FOID MU HK/NI证件号码/P1 录入身份证信息

``` Text
SSR FOID 航司 HK(订座状态已确认)/NI身份证号码/P1 关联PNR中第一位旅客

SSR FOID MU HK/NI110100199902029101/P1
SSR FOID MU HK/NI110100199902029101/P2
SSR FOID MU HK/NI110100199902029101/P3
```


6. OSI 航司 CTCT联系电话

``` Text
格式
CTCT联系电话(协调人)
>OSI ZH CTCT13611110000

CTCM 本人联系方式
>OSI ZH CTCM13611110000/P1
```


7. 封口 \



8. 提取票面信息

  1. RT PNR





9. ETDZ:1 出票指令

  ```JSON
> ETDZ:打票机序号
> ETDZ:1
```


  1. ETRY 重新出票指令




