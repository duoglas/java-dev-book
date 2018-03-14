## maven

#### 学习目标

* 使用maven构建复杂工程
* 排查maven包依赖问题
* 排查maven包部署问题

#### 学习资料

http://maven.apache.org/guides/getting-started/index.html

### 拓展：多模块工程

#### 学习目标

理解原理，熟练使用

#### 学习资料

https://maven.apache.org/guides/mini/guide-multiple-modules.html

拓展阅读：

http://juvenshun.iteye.com/blog/305865

### 拓展：maven profile

#### 学习目标

理解原理，学会使用

#### 学习资料

[http://maven.apache.org/guides/introduction/introduction-to-profiles.html](http://maven.apache.org/guides/introduction/introduction-to-profiles.html)

拓展阅读：

[https://www.zybuluo.com/haokuixi/note/25985](https://www.zybuluo.com/haokuixi/note/25985)

[http://blog.csdn.net/mhmyqn/article/details/24501281](http://blog.csdn.net/mhmyqn/article/details/24501281)

### 实践

* 创建多模块工程
  * mvn archetype:generate -DarchetypeGroupId=org.codehaus.mojo.archetypes -DarchetypeArtifactId=pom-root

  * mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart

  * mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-webapp

* 理解SNAPSHOT包与正式包区别

* 理解mvn package时依赖的SNAPSHOT包更新机制，如何强制更新

* 理解mvn package时寻找加载一个依赖包的顺序

* 学会如何检查工程中依赖的某个包的实际版本，学习影响依赖版本的不同因素和优先级

* 学会使用maven jetty插件部署web工程

* 学会使用maven执行单元测试、跳过执行单元测试

* 尝试mvn install、mvn deploy



