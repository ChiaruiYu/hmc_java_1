# Java 绪论作业点评

这里是大家在程序上存在的普遍问题和一些做得好的地方。

1. package 的名字 .java文件名字 和类名等，都要用英文命名，<u>**不要用中文**</u>

2. for 循环下面的语句块 依然没有用括号括起来。造成for只作用于接下来的一句话(这个已经强调过好几次了)

3. 同理接上面，一些数值如果是多次使用，最好定义一个变量存储它，然后用在各个地方，而不是每次都去计算一遍。

4. 变量命名要有意义，最好不要用a,b,c这样去命名，有些同学做的挺好，born,death等都很形象，让人一看就懂这个变量是什么意思？

5. 题意没有看清楚，一道题目是计算 未来5年每年的人口，有些同学只算了最后一年的人口。

6. 计算人口的题目，一些数字直接拿来用，让人不知道这个数字是怎么算出来的。比如，如果你想表达一天的秒数，就用 secondesInOneDay = 60*60*24 这样先定义，然后在下面使用。

7. 计算人口，一年的人口变化为delta,那如果你要打印5年的，那每年都要+/-这个delta。

   ```java
    for(int i=0;i<5;++i){
   
   ​      System.out.println(population)  // 错误`
   
   ​      System.out.println(population+ changeInOneYear) //正确`
   
   ​ }
   ```

   ​          

8. 题目若可以用循环，不要一句句单独写。这次是让你做5次，那如果做100次呢？

9. 提交作业要写名字！！！ 下次若不行就当没有交了。请保证你提交的东西是完整的，这样才能方便其他人去处理。

10. 不要在word里面嵌入 .java文件，要单独拿出来。

11. 有同学不仅提交了代码，还提交了代码运行后的结果的截图，这个很好，请大家下次也这么做。方便老师查阅结果。