# fuzzing_resources


# 1. AFL 源码

AFL - google 维护版
https://github.com/google/AFL

AFL - 原始版 （不支持新版LLVM）
https://lcamtuf.coredump.cx/afl/

AFL++ 一个衍生版
https://github.com/AFLplusplus/AFLplusplus

AFL的运行可以看自带文档，也可以搜索网络上的文章，如http://zeroyu.xyz/2019/05/15/how-to-use-afl-fuzz/  ，  https://paper.seebug.org/841/
AFL的源码阅读，可以自行阅读，或者搜索网络上的文章，如https://bbs.pediy.com/thread-254705.htm

# 2. Fuzz 网络协议

# 使用AFL
可以使用Preeny hook，
https://github.com/zardus/preeny
或者 https://github.com/zyingp/desockmulti
；或者改造代码 https://www.fastly.com/blog/how-to-fuzz-server-american-fuzzy-lop

# AFLNet

https://github.com/aflnet/aflnet

# Peach
https://www.peach.tech/products/peach-fuzzer/

# Boofuzz
https://github.com/jtpereyda/boofuzz

# 3. 一些有用工具

## 自带的测试用例精简工具 afl-cmin afl-tmin

## 查看测试覆盖 afl-cov
https://github.com/mrash/afl-cov

## 工具集 afl-utils
https://github.com/rc0r/afl-utils

## 2020年UNIFUZZ的工具包
包括了种子集、不同fuzzer配置、待测试程序配置、crash分析等代码
https://github.com/unifuzz/overview


# 4. LLVM

https://github.com/google/AFL/tree/master/llvm_mode
http://llvm.org/docs/WritingAnLLVMPass.html
https://github.com/Evian-Zhang/llvm-ir-tutorial

# 5. KLEE

## KLEE官网
http://klee.github.io/

## Kleeafl
https://github.com/julieeen/kleefl

# 6. 一些测试对象
[Fuzzing targets](./fuzzing_targets.md)

# 7. 论文

最新Fuzzing论文
https://github.com/wcventure/FuzzingPaper

Yingpei Zeng, Mingmin Lin, Shanqing Guo, Yanzhao Shen, Tingting Cui, Ting Wu, Qiuhua Zheng, Qiuhua Wang, [MultiFuzz: A Coverage-Based Multiparty-Protocol Fuzzer for IoT Publish/Subscribe Protocols](https://zyingp.github.io/files/MultiFuzz.pdf), Sensors, Vol.20, No.18, 5194, 2020 

建议使用Mendeley Desktop或者Zotero 管理文献

