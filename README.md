# AndroidCodeCheck
> config only once, create nice code!

this idea come from [How to improve quality and syntax of your Android code](http://vincentbrison.com/2014/07/19/how-to-improve-quality-and-syntax-of-your-android-code/)

Click Star if you like this plugin, thank you!

# Feature:
- Check code by checkstyle, findbugs, pmd and lint
- Do not have to configure their own(because configuration file from google,IBM,...), in the plug-in has been configured.
- Easy to use, easy to check
- Suitable for teamwork

# How to use
1. add plugin to app.gradle file
```
apply from: 'https://raw.githubusercontent.com/haodynasty/AndroidCodeCheck/master/quality.gradle'
...
```
2. check code by gradle command
```
gradlew check
```

3. check report
you can check report from checkstyle, findbugs, pmd and lint.

report file path: app/build/reports

# demo

- [How to improve quality and syntax of your Android code](http://vincentbrison.com/2014/07/19/how-to-improve-quality-and-syntax-of-your-android-code/), [中文翻译](https://yq.aliyun.com/articles/57838)
- [vb-android-app-quality](https://github.com/vincentbrison/vb-android-app-quality)
- [more config](https://gist.github.com/haodynasty/10860f4ab9c2bb231e40b4cf69cb724a)
- [checkstyle help](http://checkstyle.sourceforge.net/), [Gradle Checkstyle doc](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.quality.Checkstyle.html)
- [findbugs doc](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.quality.FindBugs.html)
- [pmd doc](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.quality.Pmd.html)
