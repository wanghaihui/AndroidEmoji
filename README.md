# AndroidEmoji

> j.s 🇨🇳

AndroidEmoji


# Features

* API > 9 
* Support load emoji from file  

## Screen Record

<img src="output/emoji-system-little.png" width="32%" />
<img src="output/emoji-common-little.png" width="32%"/>
<img src="output/emoji-all-little.png" width="32%"/>
 
# XhsEmoticonsKeyboard

If you need a keyboard --> [XhsEmoticonsKeyboard](https://github.com/w446108264/XhsEmoticonsKeyboard) 

<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/chat-qqemoticon.png" width="12%" /> 
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/chat-qqplug.png" width="12%" /> 
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/chat-qqfav.png" width="12%" />  
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/chat-bigimage.png" width="12%" /> 
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/chat-userdefui.png" width="12%" /> 
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/chat-text.png" width="12%" />  
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/simple-comment.png" width="12%" /> 
<img src="https://github.com/w446108264/XhsEmoticonsKeyboard/raw/master/output/main.png" width="12%" /> 

# Samples

You can [download a sample APK](https://github.com/w446108264/AndroidEmoji/raw/master/output/simple.apk) 
 
 
# Gradle Dependency

Users of your library will need add the jitpack.io repository:

```xml  
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```

and:

```xml
dependencies { 
    compile 'com.github.w446108264:AndroidEmoji:1.0.0'
}
```
--

### Simple

```java

        SpannableStringBuilder spannableStringBuilder = new SpannableStringBuilder(content); 
        Spannable spannable = EmojiDisplay.spannableFilter(tv_content.getContext(),
                spannableStringBuilder,
                content,
                getFontHeight(tv_content));
        tv_content.setText(spannable);

```
 
 
# Contact & Help

Please fell free to contact me if there is any problem when using the library.

* email: shengjun8486@gmail.com 


