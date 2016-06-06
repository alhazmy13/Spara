
# Spara
![](https://img.shields.io/badge/Platform-Android-brightgreen.svg)
![](https://img.shields.io/packagist/l/doctrine/orm.svg)
![](https://img.shields.io/badge/version-0.0.0-blue.svg)



### What happens while Activity's State is being Saved/Restored
------
>When Activity's onSaveInstanceState is called. Activity will automatically collect View's State from every single View in the View hierachy. Please note that only View that is implemented View State Saving/Restoring internally that could be collected the data from. Once onRestoreInstanceState is called. Activity will send those collected data back to the View in the View hierachy that provides the same android:id as it is collected from one by one.

>Thoes View's state are automatically saved but the Activity's member variables are not. They will be destroyed along with Activity. You have to manually save and restore them through onSaveInstanceState and onRestoreInstanceState method

#### What Spara can do?
------

## Installation
------
**Maven**
```xml
<dependency>
<groupId>net.alhazmy13.Spara</groupId>
<artifactId>library</artifactId>
<version>0.0.0</version>
</dependency>
```


**Gradle**
```gradle
dependencies {
	compile 'net.alhazmy13.Spara:library:0.0.0'
}
```

# Usage

## License
------

The MIT License (MIT)

Copyright (c) 2015 Abdullah Alhazmy

> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
