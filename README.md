# AndroidCodeCheck
check code by checkstyle, findbugs, pmd and lint

# How to use
1. add plugin to app.gradle file
```
apply plugin: 'com.android.application'
apply from: 'https://raw.githubusercontent.com/haodynasty/AndroidCodeCheck/master/quality.gradle'
...
```
2. check code by command
```
gradlew check
```

3. check report
you can check report from checkstyle, findbugs, pmd and lint.

report file path: app/build/reports

# demo

- [提高代码质量－工具篇](https://yq.aliyun.com/articles/57838)
- [vb-android-app-quality](https://github.com/vincentbrison/vb-android-app-quality)
- [more config](https://gist.github.com/haodynasty/10860f4ab9c2bb231e40b4cf69cb724a)
- [checkstyle help](http://checkstyle.sourceforge.net/), [Gradle Checkstyle doc](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.quality.Checkstyle.html)
- [findbugs doc](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.quality.FindBugs.html)
- [pmd doc](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.quality.Pmd.html)
