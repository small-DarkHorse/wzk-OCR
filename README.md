# WangZK-project
provider  help and use for other people.

在项目的build.gradle添加JitPack仓库

allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
Step 2. 添加依赖
在需要使用的module中添加依赖

dependencies {
	compile 'com.github.small-DarkHorse.WangZK-project:PictureSelector:1.0'
}
