[ ![Download](https://api.bintray.com/packages/alorma/maven/github-sdk/images/download.svg) ](https://bintray.com/alorma/maven/github-sdk/_latestVersion)

#GithubAndroidSdk

## USAGE

Add repository url in yout rop-level `build.gradle`

``` groovy
maven {
    url  "http://dl.bintray.com/alorma/maven"
}
```

Add dependency in your project `build.gradle`

``` groovy


    compile 'com.github.alorma:github-sdk:1.0.1'
```

## FORK

In order to use this sdk, you must enable three metadata keys in your `AndroidManifest.xml`

```
<meta-data
    android:name="com.alorma.github.sdk.client"
    android:value="@string/gh_client_id"/>

<meta-data
    android:name="com.alorma.github.sdk.secret"
    android:value="@string/gh_client_secret"/>

<meta-data
    android:name="com.alorma.github.sdk.oauth"
    android:value="@string/gh_client_callback"/>
```

In Gitskarios, this keys are hidden from repository, so you should create your own string files, or place it directly in `value`

##LICENSE

The MIT License (MIT)

Copyright (c) 2015 Bernat Borrás Paronella

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.