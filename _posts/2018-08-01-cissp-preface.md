CISSP官方指南前言部分

## **CBK 8个域**

| 域             | 章节           |
| -------------- | -------------- |
| 安全和风险管理 | 第 1 ~ 第 4 章 |
| 资产安全       | 第 5 章        |
| 安全工程       | 第 6 ~ 10 章   |
| 通信与网络安全 | 第 11 ~ 12 章  |
| 身份和访问管理 | 第 13 ~ 14 章  |
| 安全评估与测试 | 第 15 章       |
| 安全运营       | 第 16 ~ 19 章  |
| 软件开发安全   | 第 20 ~ 21 章  |

## **评估测试**

1.**以下哪种类型的访问控制会争取去发现不需要的, 未授权的或者非法行为或活动的证据？**

- A. 预防			
	 B. 威慑			
	 <u>C. 检测</u>		
- D. 纠正

2.**定义和详细说明区分良好的密码选择和非良好密码选则的方面。** 

- A. 难以猜测或不可预测

- B. 满足最小长度要求

- C. 满足特定的复杂性要求

- <u>D. 以上所有</u>

  ```
  强密码难以猜测，不可预测而且长度不低于下限， 能确保无法计算得到明确的密码数据。
  
  强密码可以随机生成， 而且可以使用所有字母，数字和标点字符。
  
  避免共享密码， 不能存储在公共可访问或者普遍可读的位置。
  
  不能以明文发送。 
  
  有条件定期更新密码
  
  限制无限次尝试用户密码，只提供必要的错误信息
  
  ```

3.**以上哪一项最有可能检测到DoS攻击？**

- A. 基于主机的IDS

- <u>B. 基于网络的IDS</u>

- C. 漏洞扫描程序

- D. 渗透测试

  ```
  IDS (Intrusion  Detection ): 根本的任务是对入侵行为做出适当的反应， 这些反应包括详细日志记录， 实时报警和有限度的反击攻击源。
  
   基于网路的IDS将检测网段中的各种数据包。
  
   基于主机的IDS: 监视单个系统， 通常运行在需要保护的主机上。 它会读取主机上的日志， 并进行异常检测。
  
  ```

4.**以下哪一项被视为拒绝服务攻击？**

- A. 假装是技术经理， 通过电话要求接待员更改他们的密码。 
- <u>B. 在上网时， 向Web服务器发送一个格式错误的URL, 导致系统消耗100%的CPU</u>
- C. 在他们通过特定子网时， 通过复制分组来拦截网络流量。
- D. 向没有请求的收件人发送消息包， 只是简单的骚扰。

5.**路由器工作在OSI模型的哪一层？**

- <u>A. 网络层</u>
- B. 第 1 层
- C. 传输层
- D. 第 5 层