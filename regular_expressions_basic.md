So let's get ready. First we need to take baby steps and in this section we will do the same. After all Rome was not built in a day and I am a firm believer in the fact that **the fastest way to learn anything is to do it slowly**.

Okay, so first thing we need to wrap our head around is what we achieve from regular expressions. Usually the problem is consisting of two steps.
* Firstly, We will be having a text to parse, which is the easy part and often you have to do nothing for that.
* Secondly, which is usually the difficult part, is to come up with a pattern to do the same.

Basics are quite easy.












But before that just remember that there is something you should be aware of. Let's call it step Zero. Those of you who has used regular expressions to certain extent, might have noticed that usually the pattern which you expect to work, doesn't give you desired result. In fact, it may also happen that a certain pattern works in one case and not in other for the same text. 

The reason for that, apart from the flavour of regular expression, is that the string pattern you specify might get processed by the language before reaching the regular expression as a pattern. 

Let's make it clear with an example. 

Suppose the string is

```
I am trying to learn regular expression, Mom.
Dinner can wait.
```
