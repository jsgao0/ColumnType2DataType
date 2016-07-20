### Mapping to Java ([Ref](https://docs.oracle.com/cd/F49540_01/DOC/java.815/a64685/basic3.htm))
|Oracle|Limit|⇒|Java|Limit|
|---|---|---|---|---|
|CHAR|2000 bytes|⇒|java.lang.String||
|VARCHAR2|4000 bytes|⇒|java.lang.String||
|LONG|2GB - 1|⇒|java.lang.String||
|NUMBER(1)|0 \| 1|⇒|boolean|True \| False|
|NUMBER([1,2])||⇒|byte|[[-2^7](https://www.wolframalpha.com/input/?i=-2%5E7), [2^7-1](https://www.wolframalpha.com/input/?i=2%5E7-1)]|
|NUMBER([1,4])||⇒|short|[[-2^15](https://www.wolframalpha.com/input/?i=-2%5E15), [2^15-1](https://www.wolframalpha.com/input/?i=2%5E15-1)]|
|NUMBER([1,9])||⇒|int|[[-2^31](https://www.wolframalpha.com/input/?i=-2%5E31), [2^31-1](https://www.wolframalpha.com/input/?i=2%5E31-1)]|
|NUMBER([1,18])||⇒|long|[[-2^63](https://www.wolframalpha.com/input/?i=-2%5E63), [2^63-1](https://www.wolframalpha.com/input/?i=2%5E63-1)]|
|NUMBER([1,38])||⇒|float|[[1.4E-45](https://www.wolframalpha.com/input/?i=1.4E-45), [3.4028235E38](https://www.wolframalpha.com/input/?i=3.4028235E38)]|
|NUMBER(1, [0,37])||⇒|float|[[1.4E-45](https://www.wolframalpha.com/input/?i=1.4E-45), [3.4028235E38](https://www.wolframalpha.com/input/?i=3.4028235E38)]|
|NUMBER(p, q)|p + q < 38|⇒|float|[[1.4E-45](https://www.wolframalpha.com/input/?i=1.4E-45), [3.4028235E38](https://www.wolframalpha.com/input/?i=3.4028235E38)]|
|NUMBER|[[-10E125](https://www.wolframalpha.com/input/?i=-10E125), [10E125](https://www.wolframalpha.com/input/?i=10E125)]|⇒|double|[[4.9E-324](https://www.wolframalpha.com/input/?i=4.9E-324), [1.7976931348623157E308](https://www.wolframalpha.com/input/?i=1.7976931348623157E308)]|
