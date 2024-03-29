#### bugs of "type conversion" , "type casting", "type coercion" , "type juggling", "type confusion", "downcast" or "upcast". 

&nbsp;
&nbsp;

useful bugs
> the code patch url is in comments at very last. You can click url after **commit**, **modified** or **Review-on** in the comment to get the code patch. 
 
|num|id|summery|remark|
|----|----|----|----|
|1|[1355123](https://bugs.chromium.org/p/chromium/issues/detail?id=1355123&q=%22type%20conversion%22%20OR%20%22type%20casting%22%20status%3DFixed&can=1)| Incorrect type conversion to check if it implements the interface|  |
|2|[1197369](https://bugs.chromium.org/p/chromium/issues/detail?id=1197369&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed&can=1)|WebGPU: Implement CopyExternalImageToTexture| the bug is about alpha type conversion, which is a kind of image attribute. |
|3|[1196966](https://bugs.chromium.org/p/chromium/issues/detail?id=1196966&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed&can=1)| [Tablet] Chrome crashes on opening download home on tablets|  |
|4|[1170237:](https://bugs.chromium.org/p/chromium/issues/detail?id=1170237&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed&can=1)|Regression: 'Hangout' crashes after right clicking in chat when red underlined| type conversion of vectors|
|5|[1051498](https://bugs.chromium.org/p/chromium/issues/detail?id=1051498&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Storage Keys are read as strings in LoginDatabase|this shouldn't have any effect, but this patch improves the readability of the code|
|6|[985991](https://bugs.chromium.org/p/chromium/issues/detail?id=985991&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|When scrolling slowly, overflow bubble has no reaction| a conversion from float to int, which lose precision, cause the display problem|
|7|[961237](https://bugs.chromium.org/p/chromium/issues/detail?id=961237&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Security: jit difference on comparison in d8| caused by type conversion from null to 0| 
|8|[930252](https://bugs.chromium.org/p/chromium/issues/detail?id=930252&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Refactor: Remove uses of unsigned long in blink| not a bug, remove unsigned type to avoid introducing bugs|
|9|[844285](https://bugs.chromium.org/p/chromium/issues/detail?id=844285&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Build error about type conversion| | 
|10|[603656](https://bugs.chromium.org/p/chromium/issues/detail?id=603656&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Type casting bug in QUIC can cause errors for large (> 4GB) transfers. | missing frame recording logic in a 32-bit machine. |
|11|[548375](https://bugs.chromium.org/p/chromium/issues/detail?id=548375&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|DCHECK_GE in rand_util.cc:24 fails for certain inputs| an overflow that was caused by casting UNIX_MAX to int |
|12|[522989](https://bugs.chromium.org/p/chromium/issues/detail?id=522989&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|safe_conversions.h’s base::IsValueInRangeForNumericType<>() is broken| range checks are incorrect whenconverting from a floating point value to an integral value ofhigher precision but lower width. |
|13|[425001](https://bugs.chromium.org/p/chromium/issues/detail?id=425001&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)| ASSERTION FAILED: repetitions > 0, UNKNOWN in blink::CSSPropertyParser::parseGridTrackRepeatFunction| a double clamped to 0 when type casting that lead to assertion failed. | 
|14|[39346](https://bugs.chromium.org/p/chromium/issues/detail?id=393464&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Element.scrollTop max value reduced| because of unnecessary type casting, the values are champled inproperly|
|15|[346626](https://bugs.chromium.org/p/chromium/issues/detail?id=346626&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Enable Android x64 Build| problems that cause crashes, warnings during the process of making x64 enable | 
|16|[324829](https://bugs.chromium.org/p/chromium/issues/detail?id=324829&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Mojom: Add array bounds debug assertions| improve type conversion for empty strings.|
|17|[309938](https://bugs.chromium.org/p/chromium/issues/detail?id=309938&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Fix build for x64 with component=static_library| A compile error occurs due to a bad type conversion| 


<br>

Bugs or problems that include type-conversion.
|id|summery|remark|
|----|----|----|
|[239879](https://bugs.chromium.org/p/chromium/issues/detail?id=239879&can=1&q=%28%22type%20conversion%22%20OR%20%22type%20casting%22%20%29%20status%3DFixed)|Allow user-selectable paper size for printers in Print Preview| Fix C++ type-conversion during development | 



