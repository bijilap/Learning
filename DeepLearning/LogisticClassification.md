## Softmax
S(y<sub>i</sub>)= e<sup>y<sub>i</sub></sup> / ∑<sub>j</sub> e<sup>y<sub>j</sub></sup>

## One Hot Encoding
One-hot refers to a group of bits among which the legal combinations of values are only those with a single high (1) bit and all the others low (0)
To represent labels in format we will have a vector (with length equal to number of classes) where the probabilty of the most likely class will tending to 1, while for other classes it would be tending to 0.

S (y) ->  [                 -> [              
            0.7,                 1,           a
            0.2,                 0,           b
            0.1                  0            c
           ]                    ]
