# Korean-Typing-Effect
This is my blog posting that explains how I designed the algorithms and code -> https://blog.naver.com/jwjung0907/222426116783 (written in Korean)

Let me briefly introduce my work.
This code can disassemble/assemble Korean sentence to vowels and consonants.
To implement typing-effect, it disassembles entire sentence,
then by adding 1 character repeatedly, it assembles them.
Here is an example of how it works:D

![test_sentence_1](https://user-images.githubusercontent.com/80532804/223392341-67cc950a-f844-4fb5-83e0-c9ed4f407f7a.gif)

Here is an code example how to use its methods

```python
import KRtype as kt

s = "안녕하세요"
d = kt.disassemble(s)
a = kt.assemble(list(d))
```

Here is detail parameter/return of two available functions

```python
def disassemble(str: string): -> string

def assemble(list: string): -> list
```
