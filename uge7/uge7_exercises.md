                                Eksamenatorier I:


## 1. Exercise 2.1-1 (page 22)
Using Figure 2.2 as a model, illustrate the operation of INSERTION-SORT on the array A = { 31, 41, 59, 26, 41, 58 }

ANSWER:
    
    step 1: { 31, 41, 59, 26, 41, 58 }

    step 2: { 26, 31, 41, 59, 41, 58 }

    step 3: { 26, 31, 41, 41, 59, 58 }

    step 4: { 26, 31, 41, 41, 58, 59 }


## 2. Exercise 2.1-3 (page 22)
Consider the searching problem:
- Input: A sequence of n numbers A = (a1, a2...an) and a value v .
- Output: An index i such that v = A[i] or the special value NIL if v does not appear in A.

Write pseudocode for linear search, which scans through the sequence, looking for v. Using a loop invariant, prove that your algorithm is correct. 
Make sure that your loop invariant fulfills the three necessary properties.
PS: But avoid using invariant this time, since it will be catched up later in the course!

ANSWER:

    LINEAR-SEARCH(A,v) 
        for i = 0 to A.length-1
            if A[i] == v
                return A[i]
            else 
                return NIL

*look up for pseudocode conventions from page 20 in the book!

## 3. Exercise 2.2-3 (page 29)
Consider linear search again (see Exercise 2.1-3). 
How many elements of the input sequence need to be checked on the average, assuming that the element being searched for is equally likely to be any element in the array? 
How about in the worst case? What are the average-case and worst-case running times of linear search in $\Theta$-notation? Justify your answers.

ANSWER:
    ??

## 4. Exercise 2.3-5 (page 39)
Referring back to the searching problem (see Exercise 2.1-3), observe that if the
sequence A is sorted, we can check the midpoint of the sequence against $v$ and
eliminate half of the sequence from further consideration. The ***binary search*** algorithm repeats this procedure, halving the size of the remaining portion of the
sequence each time. Write pseudocode, either iterative or recursive, for binary
search. Argue that the worst-case running time of binary search is $\Theta(\lg n)$.

ANSWER:

    

## 5. Exercise 2.3-6 (page 39)



## 6. Exercise 2.3-1 (page 37)



## 7. Exercise 2.3-2 (page 37)



## 8. Exercise 2-4 (page 41, a, b, c)



## 9. Exercise 2.3-7 (page 39)

                                Eksamenatorier II:


## 1. 

## 2. 
 
## 3. 

## 4. 

## 5. 

## 6. 