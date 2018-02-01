# RoundLayout
RoundLayout

Xml圆角布局

<pre><code>&lt;com.prohua.roundlayout.RoundAngleFrameLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:radius="15dp"&gt;
        ...todo
&lt;/com.prohua.roundlayout.RoundAngleFrameLayout&gt;
</code></pre>

### 参数 radius 圆角半径 单位dp

## How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}Copy
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.Deepblue1996:RoundLayout:1.0'
	}
