[![GitHub release](https://img.shields.io/github/release/abcdqianlei1990/TimerButton.svg)](https://github.com/abcdqianlei1990/TimerButton/releases)
# TimerButton
倒计时按钮，支持继续上次的倒计时

## autoCounting = true
![image](https://github.com/abcdqianlei1990/TimerButton/blob/master/gif/autoCountingTrue.gif)

## autoCounting = false
![image](https://github.com/abcdqianlei1990/TimerButton/blob/master/gif/autoCountingFalse.gif)

## Sample
see ![sample](https://github.com/abcdqianlei1990/TimerButton/tree/master/sample)

## Attrs
|name|type|note|
|:----|:------|:------|
|autoCounting|boolean|if need auto counting|
|countingStart|int|counting down from ${countingStart}|

## How to do
### step 1.Add it in your root build.gradle at the end of repositories:
```groovy
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
### step 2. Add the dependency
```groovy
	dependencies {
          ...
	        compile 'com.github.abcdqianlei1990:TimerButton:1.0'
	}
```
