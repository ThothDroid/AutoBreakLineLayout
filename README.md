[![](https://jitpack.io/v/ThothDroid/AutoBreakLineLayout.svg)](https://jitpack.io/#ThothDroid/AutoBreakLineLayout)

# AutoBreakLineLayout
=================

AutoBreakLineLayout is an android ViewGroup show view child with line break like TextView show text.

![image](https://github.com/zerozhiqin/AutoBreakLineLayout/blob/master/images/pic.png)

Layout code :
```xml
  
    <dev.misono.breaklinelayout.BreakLineLayout
        android:id="@+id/break_line_layout"
        app:shareWidth="true"
        app:maxLines="all"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />

```

## Install

Add this to your `settings.gradle.kts` at the end of repositories:
```
dependencyResolutionManagement {
  repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
  repositories {
    mavenCentral()
    maven { url = uri("https://jitpack.io") }
  }
}
```
Then add this dependency to your `build.gradle.kts` file:
```
dependencies {
  implementation("com.github.ThothDroid:AutoBreakLineLayout:1.0.0")
}
```
> [!NOTE]
> For the implementation for other build systems like `Groovy` see [here](https://jitpack.io/#ThothDroid/AutoBreakLineLayout/)

## Version Catalog
### 1.0.0
first release
- upgraded gradle
### latest Version
`1.0.0`