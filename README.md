# proj194-SMx-encryption-algorithm-on-OneOS

## 项目描述
密码算法主要分为三类：对称密码算法、 非对称密码算法、摘要算法。对称算法是指加密密钥和解密密钥相同的密码算法，常见对称算法有DES、AES、SM4；非对称算法则加密密钥和解密密钥不相同，常见非对称算法有RSA、ECC、SM2；而摘要算法把任意长的输入消息数据转化成固定长度的输出数据的一种密码算法，又称散列函数、哈希函数或杂凑函数、单向函数等，摘要算法没有密钥，常见摘要算法有MD5、SHA、SM3。上述算法中SM2、SM3、SM4为中国制定的算法标准，即国密算法或商用密码算法（SM为商密的拼音首字母）。
赛题的目标是在 OneOS 上完成SM2、SM3、SM4中一种或多种国密算法的轻量级实现，以满足资源受限的物联网硬件使用。国密算法实现可参考GmSSL或opessl中国密算法部分，相关密码算法标准以国密密码管理局发布的国标为准。

## 源码

- [GmSSL](https://www.gmssl.cn/gmssl/index.jsp)
- [openssl](https://github.com/openssl/openssl)
- [mbedtls](https://github.com/Mbed-TLS/mbedtls)

## 项目导师
王雷

- gitee: https://gitee.com/raymondwung
- email wanglei<wanglei1@cmiot.chinamobile.com>

## 难度
中等

## 文档
[OneOS文档中心](https://os.iot.10086.cn/v2/doc/homePage)

## License
Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标
注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

第一题：完成国密算法的轻量级实现
-	在 OneOS提供的开发版上，完成SM2、SM3、SM4中一种或多种国密算法的轻量级实现，要求代码尺寸及内存占用尽可能少，与mbedtls中对应的国际算法ECDSA、SHA256、AES的资源占用及性能相当或更优。

**选择该赛题的支持**  
开发套件支持：提供给参赛队伍开发套件，此开发板万耦天工板载STM32 F103芯片:144引脚，512K FLASH，支持GSM/GPRS /LORA /WIFI/蓝牙、LCD、摄像头、温湿度等模块。并具有丰富的例程demo，OneOS学院提供手把手教学视频，方便同学们上手使用。  
获奖激励：公司对获奖同学提供入职绿色通道，获得全国总决赛二等奖、三等奖的同学可以免笔试，直接进入面试环节。获得全国总决赛一等奖的同学可以直接进入终面环节。  
技术答疑指导：针对OneOS操作系统及本赛题技术要点，资深研发工程师提供专业的技术支持、指导，全程辅导技术方案的实现。  
技术资料：提供相关技术资料和对应索引，指导赛题方向。  
