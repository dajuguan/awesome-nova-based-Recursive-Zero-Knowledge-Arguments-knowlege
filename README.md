# awesome-nova-based-Recursive-Zero-Knowledge-Arguments-knowlege
Nova学习小组整理的基于Nova的递归零知识证明资料。

# Nova学习小组资料
- [郭宇@安比: A short introduction to Nova [EN]](https://www.youtube.com/watch?v=hq-1bLVz59w&t=324s)
- [郭宇@安比: Nova - Recursive SNARKs without trusted setup [中文]](https://www.youtube.com/watch?v=l19roUItyUE)
- [白菜: 三篇Nova系列基础文章](https://learnblockchain.cn/article/5978) 
- [Po: 深入理解Nova IVC Scheme中的循环曲线和主从电路](https://learnblockchain.cn/article/6097)
- 23/07/01会议梳理了Nova的verifier电路的constrains及运算，以及primary电路和secondary电路的交互，以及之前Nova实现存在的Soundness漏洞, [录像文件](https://www.youtube.com/watch?v=gopJn_QAdqU&list=PLbQFt1T_44DwtG7Qv_BEyCP_t37qT9yMV&index=1)
- 23/07/09会议讨论了Nova中constrain system里面的运算优化的疑点、延展性攻击和一些最新的库，[录像文件](https://www.youtube.com/watch?v=z4aEW9hxEs8&list=PLbQFt1T_44DwtG7Qv_BEyCP_t37qT9yMV&index=2)
- 23/07/16会议郭宇老师解读了Spartan论文的前半部分，[录像文件](https://www.youtube.com/watch?v=at2U9iOvEBg&list=PLbQFt1T_44DwtG7Qv_BEyCP_t37qT9yMV&index=3)
- 23/09/02会议讨论了Supernova及其Read only memory的实现，[录像文件](https://www.youtube.com/watch?v=xmMF5qn1T0M)

# 视频讲解
- [by 作者Srinath Setty [EN]](https://www.youtube.com/watch?v=mY-LWXKsBLc)
- [Nova Crash Course with **Justin Drake**  [EN]](https://www.youtube.com/watch?v=SwonTtOQzAk&t=2815s)

# Classic Nova
- [Nova: Recursive Zero-Knowledge Arguments from Folding Schemes](https://eprint.iacr.org/2021/370)
- [Revisiting the Nova Proof System on a Cycle of Curves](https://eprint.iacr.org/2023/969)
- [Supernova:a new recursive proof system for incrementally producing succinct proofs of correct execution of programs on a stateful machine with a particular instruction set](https://eprint.iacr.org/2022/1758)
- [(CycleFold: Folding-scheme-based recursive arguments over a cycle of elliptic curves](https://eprint.iacr.org/2023/1192)
  - CycleFold中主从电路中的`从`电路只用来做单个scalar multiplication(1000-1500个乘法门),使得从电路的电路规模减小了一个数量级

# 🔥🔥🔥 Nova extensions
## with high-degree gates
- [Hypernova: Enhanced Nova for for customizable constraint systems](https://eprint.iacr.org/2023/573)
- [ProtoStar: Generic Efficient Accumulation/Folding for Special Sound Protocols](https://eprint.iacr.org/2023/620)
- [ProtoGalaxy: Efficient ProtoStar-style folding of multiple instances](https://eprint.iacr.org/2023/1106)

## with Lookup
- [Unlocking the lookup singularity with Lasso](https://people.cs.georgetown.edu/jthaler/Lasso-paper.pdf)

# Accelerating Nova
- [Parallelizing Nova](https://zkresear.ch/t/parallelizing-nova-visualizations-and-mental-models-behind-paranova/198)
- [Super nova & parallelizing nova](https://zuzalu.streameth.org/session/169)
## PCS
- [Spartan2](https://github.com/microsoft/Spartan2)

# 探索代码
- [Microsoft Nova implementation](https://github.com/microsoft/Nova)
- [RiscZero Nova](https://github.com/hero78119/risc0-nova)
- [Superper nova pr](https://github.com/microsoft/Nova/pull/204) has been moved to [lurk-lab/arecibo branch](https://github.com/hero78119/arecibo/tree/arecibo_supernova) to further polish its interfaces 
## Nova extensions 
- [PSE HyperNova](https://github.com/privacy-scaling-explorations/Nova/tree/hypernova)
- [PSE Supernova](https://github.com/microsoft/Nova/pull/204)
- [ProtoGalaxy PoC implementation](https://github.com/arnaucube/protogalaxy-poc)

# Applications
- [MACI v2:MACI + Nova + ElGamal PoC](https://github.com/privacy-scaling-explorations/MACI-v2)
## Circuit integeration
- [Middleware to compile Circom circuits to Nova](https://github.com/nalinbhardwaj/Nova-Scotia)
## On-chain verifier
- [Solidity implementation of Nova proving system verifier](https://github.com/lurk-lab/solidity-verifier)

# 背景知识
- [用于生成Transcript的Sponge API ](https://hackmd.io/bHgsH6mMStCVibM_wYvb2w)

  ## 循环曲线相关
  - [difference between base field and scalar field](https://crypto.stackexchange.com/questions/66436/for-an-elliptic-curve-what-is-the-difference-between-the-base-field-modulus-q)
  - [order of ecc](https://medium.com/asecuritysite-when-bob-met-alice/whats-the-order-in-ecc-ac8a8d5439e8)
  - [Scalable Zero Knowledge via Cycles of Elliptic Curves](https://eprint.iacr.org/2014/595.pdf)
  - [The halo2 book](https://zcash.github.io/halo2/index.html)
  - [Nova based zk VM:循环曲线这一节讲解不错](https://hackmd.io/@monyverse/H1XSVmHNh#Curve-Cycling)
  ## bellperson overview
  - [Bellman: zk-SNARKs in Rust](https://electriccoin.co/blog/bellman-zksnarks-in-rust/)


