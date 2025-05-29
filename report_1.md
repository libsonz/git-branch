
# Table of Contents

1.  [Note:](#org4deae23)
2.  [Terminology Alert:](#org388e437)
3.  [Research:](#orgee1a37c)
    1.  [LSTM - Long Short-Term Memory:](#org62c57e9)
        1.  [source:](#org949fe5f)
        2.  [info](#orgef50dab)
    2.  [The Essential Main Ideas of Neural Network:](#orgc47b773)
        1.  [source:](#org06b99d3)
        2.  [content:](#orgf9eea57)
    3.  [Backpropagation Main Ideas:](#org2ce7688)
        1.  [source:](#org67cd5dd)
        2.  [content:](#org0274221)
    4.  [Gradient Descent:](#org22316dd)
        1.  [source:](#org476b569)
        2.  [content:](#orga6d3104)



<a id="org4deae23"></a>

# Note:

-   about Deep Learning for sequence prediction (trajectory).
    -   given the past movement, predicts its future path.
-   the project uses the seq2seq model:
    -   encoder
    -   LSTM
    -   decoder


<a id="org388e437"></a>

# Terminology Alert:

-   RNN ?
-   active function (sigmoid and tanh) ?
-   LSTM ?
-   NN ?
-   backpropagation ?
-   hidden layer ?
-   pytorch ?
-   gradient descent ?


<a id="orgee1a37c"></a>

# Research:


<a id="org62c57e9"></a>

## LSTM - Long Short-Term Memory:


<a id="org949fe5f"></a>

### source:

-[statQuest-LSTM](https://www.youtube.com/watch?v=YCzL96nL7j0)


<a id="orgef50dab"></a>

### info

![img](../../notes/org-images/LSTM.png)

:ID:       642d1a01-2548-4bc5-b0c3-3dc330d4d947

1.  First stage - Forget Gate:

    -   determines what percentage of
        Long-term Memory will be remembered
        (increase | decrease).

2.  Second Stage - Input Gate:

    -   determines how we should update the
        Long-term Memory with 2 blocks:
        -   Potential Long-term Memory.
        -   % Potential Memory to Remember.

3.  Third Stage - Output Gate:

    -   determines the output of LSTM with
        2 blocks:
        -   Potential Short-term Memory.
        -   % Potential Memory to Remember.


<a id="orgc47b773"></a>

## The Essential Main Ideas of Neural Network:


<a id="org06b99d3"></a>

### source:

-   [statQuest - Main idea of NN](https://www.youtube.com/watch?v=CqOfi41LfDw)


<a id="orgf9eea57"></a>

### content:

1.  basic description:

    -   NN&rsquo;s function is to create a *squiggle* to fit as much as possible
        real points(values) of the dataset with particular conditions.
    -   **weight** : multiplication.
    -   **biases** : addition.


<a id="org2ce7688"></a>

## Backpropagation Main Ideas:


<a id="org67cd5dd"></a>

### source:

-   


<a id="org0274221"></a>

### content:


<a id="org22316dd"></a>

## Gradient Descent:


<a id="org476b569"></a>

### source:

-   


<a id="orga6d3104"></a>

### content:

-   

