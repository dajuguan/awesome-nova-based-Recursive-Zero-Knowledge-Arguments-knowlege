# awesome-nova-based-Recursive-Zero-Knowledge-Arguments-knowlege
Nova学习小组整理的基于Nova的递归零知识证明资料。

## Nova学习小组资料
- [郭宇@安比: A short introduction to Nova [EN]](https://www.youtube.com/watch?v=hq-1bLVz59w&t=324s)
- [郭宇@安比: Nova - Recursive SNARKs without trusted setup [中文]](https://www.youtube.com/watch?v=l19roUItyUE)
- [白菜: 三篇Nova系列基础文章](https://learnblockchain.cn/article/5978) 
- [Po: 深入理解Nova IVC Scheme中的循环曲线和主从电路](https://learnblockchain.cn/article/6097)
- 23/07/01会议梳理了Nova的verifier电路的constrains及运算，以及primary电路和secondary电路的交互，以及之前Nova实现存在的Soundness漏洞, [录像文件](https://meeting.tencent.com/user-center/shared-record-info?id=42bf96d8-3bdc-4785-bb71-71706e8dcfd8&form=-1&click_source_for_middle_login=2&app_lang=zh-cn%2Czh-cn&app_version=3.17.6.405&app_sdk_id=0300000000&app_publish_channel=TencentInside&os_version=13.1.0&os_name=Mac&c_district=0&app_instance_id=2)
- 23/07/09会议讨论了Nova中constrain system里面的运算优化的疑点、延展性攻击和一些最新的库，[录像文件]( https://meeting.tencent.com/user-center/shared-record-info?id=d117dc99-905c-4316-b14e-e9bcebbd90ac&from=6&click_source_for_middle_login=2&app_lang=zh-cn%2Czh-cn&app_version=3.18.2.431&app_sdk_id=0300000000&app_publish_channel=TencentInside&os_version=13.1.0&os_name=Mac&c_district=0&app_instance_id=2)
- 23/07/16会议郭宇老师解读了Spartan论文的前半部分，[录像文件](https://meeting.tencent.com/user-center/shared-record-info?id=7e947cb4-2899-422a-93a0-7ae081be3216&from=6&click_source_for_middle_login=2&app_lang=zh-cn%2Czh-cn&app_version=3.18.2.431&app_sdk_id=0300000000&app_publish_channel=TencentInside&os_version=13.1.0&os_name=Mac&c_district=0&app_instance_id=2)

## 视频讲解
- [by 作者Srinath Setty [EN]](https://www.youtube.com/watch?v=mY-LWXKsBLc)
- [Nova Crash Course with **Justin Drake**  [EN]](https://www.youtube.com/watch?v=SwonTtOQzAk&t=2815s)
## 论文
- [Nova: Recursive Zero-Knowledge Arguments from Folding Schemes](https://eprint.iacr.org/2021/370.pdf)
- [Revisiting the Nova Proof System on a Cycle of Curves](https://eprint.iacr.org/2023/969)
## 椭圆曲线的base field和scalar field
- [difference between base field and scalar field](https://crypto.stackexchange.com/questions/66436/for-an-elliptic-curve-what-is-the-difference-between-the-base-field-modulus-q)
- [order of ecc](https://medium.com/asecuritysite-when-bob-met-alice/whats-the-order-in-ecc-ac8a8d5439e8)
## 循环曲线
- [Scalable Zero Knowledge via Cycles of Elliptic Curves](https://eprint.iacr.org/2014/595.pdf)
- [The halo2 book](https://zcash.github.io/halo2/index.html)
- [Nova based zk VM:循环曲线这一节讲解不错](https://hackmd.io/@monyverse/H1XSVmHNh#Curve-Cycling)
## 代码
- [Microsoft Nova implementation](https://github.com/microsoft/Nova)
- [Middleware to compile Circom circuits to Nova](https://github.com/nalinbhardwaj/Nova-Scotia)
- [HyperNova](https://github.com/privacy-scaling-explorations/Nova/tree/hypernova)
## 其他
- [用于生成Transcript的Sponge API ](https://hackmd.io/bHgsH6mMStCVibM_wYvb2w)

