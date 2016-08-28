## Softmax
S(y<sub>i</sub>)= e<sup>y<sub>i</sub></sup> / ∑<sub>j</sub> e<sup>y<sub>j</sub></sup>

## One Hot Encoding
One-hot encoding refers to a group of bits among which the legal combinations of values are only those with a single high (1) bit and all the others low (0)
To represent labels in format we will have a vector (with length equal to number of classes) where the probabilty of the most likely class will be 1, while for other classes it would be  0.

```
S (y) ->    [               L ->  [              
            0.7,                 1,           class A
            0.2,                 0,           class B
            0.1                  0            class B
            ]                    ]
```

This representation becomes inefficient when you a millions of classes, considering that most of the values will be 0

## Cross Entropy

Cross entropy can be used to compare output of the classifier with that of the expected hot-encoded vector corresponding to the lables.

```
D(S,L) = - ∑<sub>i</sub>L<sub>i</sub> log(S<sub>i</sub>)
```

## Multinomial Logisitic Classification
    
       Linear Model
Input -----------------> Logit  ----------> Softmax --------> Cross Entropy
