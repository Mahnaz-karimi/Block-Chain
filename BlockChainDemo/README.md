# BlockChainDemo

* [Link to tutorial](https://medium.com/programmers-blockchain/create-simple-blockchain-java-tutorial-from-scratch-6eeed3cb03fa)

* Output:
```Terminal
/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/bin/java -Dfile.encoding=UTF-8 -classpath "/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/charsets.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/deploy.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/cldrdata.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/dnsns.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/jaccess.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/jfxrt.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/localedata.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/nashorn.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/sunec.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/sunjce_provider.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/sunpkcs11.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/ext/zipfs.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/javaws.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/jce.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/jfr.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/jfxswt.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/jsse.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/management-agent.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/plugin.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/resources.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/jre/lib/rt.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/ant-javafx.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/dt.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/javafx-mx.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/jconsole.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/packager.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/sa-jdi.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_121.jdk/Contents/Home/lib/tools.jar:/Users/diana/Desktop/git/BlockChainG4 /Demo/blockchainDemo/target/classes:/Users/diana/.m2/repository/com/google/code/gson/gson/2.8.1/gson-2.8.1.jar:/Users/diana/.m2/repository/org/springframework/boot/spring-boot-autoconfigure/2.1.1.RELEASE/spring-boot-autoconfigure-2.1.1.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/boot/spring-boot/2.1.1.RELEASE/spring-boot-2.1.1.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-context/5.1.3.RELEASE/spring-context-5.1.3.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-aop/5.1.3.RELEASE/spring-aop-5.1.3.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-expression/5.1.3.RELEASE/spring-expression-5.1.3.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-web/5.1.3.RELEASE/spring-web-5.1.3.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-beans/5.1.3.RELEASE/spring-beans-5.1.3.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-core/5.1.3.RELEASE/spring-core-5.1.3.RELEASE.jar:/Users/diana/.m2/repository/org/springframework/spring-jcl/5.1.3.RELEASE/spring-jcl-5.1.3.RELEASE.jar" NoobChain
Trying to Mine block 1... 
Block Mined!!! : 00000df5ebfeb263909e92b75024482e046c207e299d59bb7f3b11190717f084
Trying to Mine block 2... 
Block Mined!!! : 0000012e097312a260004afd7395d4e0799b95f88bf96183768d04aaa43fd6da
Trying to Mine block 3... 
Block Mined!!! : 00000a04891bf85b2d11105bfc336b84ce4f6a65da4019f33606aa38a590c2b1

Blockchain is Valid: true

The block chain: 
[
  {
    "hash": "00000df5ebfeb263909e92b75024482e046c207e299d59bb7f3b11190717f084",
    "previousHash": "0",
    "data": "Hi im the first block",
    "timeStamp": 1544790473925,
    "nonce": 1255804
  },
  {
    "hash": "0000012e097312a260004afd7395d4e0799b95f88bf96183768d04aaa43fd6da",
    "previousHash": "00000df5ebfeb263909e92b75024482e046c207e299d59bb7f3b11190717f084",
    "data": "Yo im the second block",
    "timeStamp": 1544790478842,
    "nonce": 85947
  },
  {
    "hash": "00000a04891bf85b2d11105bfc336b84ce4f6a65da4019f33606aa38a590c2b1",
    "previousHash": "0000012e097312a260004afd7395d4e0799b95f88bf96183768d04aaa43fd6da",
    "data": "Hey im the third block",
    "timeStamp": 1544790479133,
    "nonce": 757957
  }
]

Process finished with exit code 0
```
