# wzk-OCR
provider  help and use for other people.
集成实现各种卡片、银行卡、身份证扫描识别

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
    implementation 'com.github.small-DarkHorse:wzk-OCR:v1.0.0'
}
