# placeholders-mistakes-finder
## 用法
Usage
### find_mistakes.sh
用于查找iOS项目多语言文件占位符数量和原文不符、占位符不正确的字符串，可以查找%d和%f两种占位符<br>
For finding out mistakes of counts and symbols of placeholders including %d and %f<br>
find_mistakes.sh .strings_file result_output_file
### find_mistakes_android.sh
用于查找安卓项目多语言文件占位符数量和原文不符、占位符不正确的字符串，可以查找整型、浮点型、字符串的占位符<br>
For finding out mistakes of counts and symbols of placeholders which place integers, float numbers or strings<br>
无法查找没有键值的字符串<br>
Cannot proceed strings of no key<br>
find_mistakes_android.sh .xml_origin_file .xml_translation_file result_output_file
