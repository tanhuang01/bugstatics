### gcc bugs of "type conversion" , "type casting", "type coercion" , "type juggling", "type confusion", "downcast" or "upcast".

|Num|id|summery|remark|
|----|----|----|----|
|01|[35642](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=35642) | short * short multiplication not vectorized on Power |  |
|02|[55058](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=55058) | [4.7/4.8 Regression] Unexpected invalid type conversion error | |
|03|[17453](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=17453) | G++ type conversion bug | It's not a real bug, but a misuse for iterator of gcc++ by a coder. |
|04|[10735](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=10735) | ICE on correct type conversion with vector| |
|05|[83383](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=83383) | [8 Regression] Wrong code with a bunch of type conversion and ternary operators | |
|06|[39415](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=39415) |static_cast used as downcast can silently lose const | | 
|07|[58119](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=58119) | [4.7/4.8/4.9 Regression] Invalid ambiguous default type conversion with only a single invalid conversion listed. | [FixUrl_link](https://gcc.gnu.org/git/?p=gcc.git;a=commitdiff;h=4e2a8865a76ea268c07d3708cb8efd7f211f87d1;hp=1a9317cf579b4afaba01774e45b037d7f6fe9854)|
|08|[36695](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=36695) | [4.3 Regression] Value-initialization of reference type is allowed. | | 


&nbsp;
&nbsp;
&nbsp;
&nbsp;

Relavant bugs.
|Num|id|summery|remark|
|----|----|----|----|
|01|[131832](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=31780)|ICE with incompatible types for ?: with "complex type" conversion |It is not a bug. It just adds a conversion from scalar arithmetic type to complex type. fixURL: http://gcc.gnu.org/viewcvs?root=gcc&view=rev&rev=131832)|
|02| [21024](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=21024) | fold generates a comparison of two operands whose types do not match| code patch is huge and do not colored, extremely hard to read. URL: https://gcc.gnu.org/legacy-ml/gcc-patches/2005-04/msg01830.html |
