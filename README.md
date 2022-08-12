### 怎样使用
#### Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
but If it is a new version of Android studio,Add it in your root setting.gradle at the end of repositories:
```
dependencyResolutionManagement {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
#### Step 2. Add the dependency
```
	dependencies {
	        implementation 'com.github.Peakmain:Common:0.0.1'
	}
```
