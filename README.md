# 对SwipeRefreshLayout进行拓展，支持上拉刷新
[![](https://jitpack.io/v/charlesgrant/PullUpRefreshLayout.svg)](https://jitpack.io/#charlesgrant/PullUpRefreshLayout)

### 引用方式

#### gradle

update project's root dir , build.gradle：

```
allprojects {
	repositories {
	//...
	maven { url "https://jitpack.io" }
	}
}
```

update app's build.gradle：

```
dependencies {
	        compile 'com.github.charlesgrant:PullUpRefreshLayout:0.1.0'
}
```

#### maven

Step 1. Add the JitPack repository to your build file

```
<repositories>
	<repository>
	    <id>jitpack.io</id>
	    <url>https://jitpack.io</url>
	</repository>
</repositories>
```

Step 2. Add the dependency

```
<dependency>
    <groupId>com.github.charlesgrant</groupId>
    <artifactId>PullUpRefreshLayout</artifactId>
    <version>0.1.0</version>
</dependency>
```

## License

    Copyright 2016 Charles, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
