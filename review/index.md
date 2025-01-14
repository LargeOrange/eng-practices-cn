# 代码评审开发者指南 

## 介绍 {#intro} 
代码评审是一些人提交一些代码片段，供另外一些人审阅的流程。    
在谷歌，我们都是通过代码评审来保证代码和产品的质量。   
这篇文档是对谷歌代码评审流程和策略的权威描述。  
这一页是我们代码评审过程的概述。这篇指南其他有两个大的部分，分别是：  

-   **[评审者指南](reviewer/)**: 代码评审者的详细指南。  
-   **[开发者指南](developer/)**: 提交变更评审的开发者的详细指南。 

## 代码评审者需要关注什么？{#look_for}  

代码评审者需要关注： 
-   **设计**： 代码是否设计良好并且适合你们的系统？  
-   **功能性**: 代码功能是否和开发者预期一致？这种方式是否对用户友好？  
-   **复杂性**: 代码能不能更简单？ 其他开发者能否快速理解并在未来很容易地使用这段代码？   
-   **测试**: 这段代码是否有真确和设计良好的自动化测试样例？   
-   **命名**: 开发者有没有正确地对变量、类、方法等命名？    
-   **注释**: 注释是否清晰有用？  
-   **代码风格**: 代码风格是否遵循[谷歌代码风格指南](http://google.github.io/styleguide/)?    
-   **文档**: 开发者是否更新了相关文档？   

参考 **[如何做代码评审](reviewer/)** 获取更多信息。

### 挑选最适合的代码评审者 {#best_reviewers}     
通常而言，你都希望找个一个*最合适*的评审者在合理的时间里对你的变更作出评审。   
最合适的评审者是那些能对你代码做出最全面最准确评价的人，一般情况下都是代码的维护者(他可能在所有者列表里也有可能不在)。 有时这意味着要不同的人阅读不同的部分。  
如果你找到理想的评审者但他没有时间，你也至少应该抄送他。   

### 当面评审 {#in_person}  
如果你是和某个合格的代码评审者结对写的代码，那么这段代码可以认为已经通过评审了。   
你也可以进行面对面的代码评审，评审者提出问题，而变更的开发人员回答问题。  

## 参见 {#seealso}  
-   **[评审者指南](reviewer/)**: 代码评审者的详细指南。 
-   **[开发者指南](developer/)**: 提交变更评审的开发者的详细指南。