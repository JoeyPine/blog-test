# 个人简介

这是一个测试狗，在转后端的路上

学过的语言
* Python
* Java
* JavaScript

喜欢做什么
1. 学习
2. 学习
3. 学习

来个JS代码`var a =1 `

来段Java代码
```java
package com.github.hcsp.shell;

public class Fork {
    public static void main(String[] args) throws Exception {
        ProcessBuilder pb = new ProcessBuilder("sh", "run.sh");
        pb.directory(getWorkingDir());
        Map<String,String> envs = pb.environment();
        envs.put("AAA","123");

        pb.redirectOutput(getOutputFile());

        pb.start().waitFor();
    }
```
