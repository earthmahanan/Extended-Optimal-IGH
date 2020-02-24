# Extended-Optimal-IGH
Run java jar command in oigh.jar file 
The first argument is the k value of the k-anonymith method.
The second argument is the number of quasi-identifiers (attributes) of the input.
The last argument is the input type.

```
$ java $JAVA_OPTS -jar oigh.jar [k] [att_no] [input_type]
```
Example :
```
$ java -Xmx25g -jar oigh.jar 3 5 RATING
```
