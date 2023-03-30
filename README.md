# discrete_time_series
 

 


 

 

 

 

 

 

 

 

Research of discrete time series.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

The task.

 

 

 

We have a discrete time series from n events with two opposite (dependent) outcomes: true (t) and false (f). Accept that the outcome true has relative frequency p*, and the outcome false has relative frequency q * = 1−p* (that is the outcome true should take place in n events u=p*n times, and the outcome false should take place in n events ū =q*n times). Consider that the outcome of event does not depend on the previous outcomes (impossibility to take into account influence of set of factors).

Example

 

                event

an outcome

Throwing a coin

Arrival to hour of number of buyers greater or smaller critical

true

Loss of a heads

Arrival to hour of number of buyers greater critical

false

Loss of a tails

Arrival to hour of number of buyers smaller critical

n

Quantity of throwing

Quantity of hours

 

Find distribution of an outcome true on a time series with probability corresponding to this distribution.

Accept distribution of outcomes true and false, as distribution of elements of a kind true and elements of a kind false on a time series with quantity of places is equal n.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

The analysis of the task.

 

 

 

The task consists in, that:

1)  Define probability of time series with the data unique (that is meaning - the only thing) selection of series true.

2)  Define probability of presence (occurrence) of a series true in length L on a time series.

3)  Define probability of continuation of a series true (or, that the same, probability of continuation of time series with an element true).

4)  Solve accompanying tasks:       

a) Define a population mean and a dispersion of length of a series true.

b) Define probable quantity of series true.

c) Define capacity of a series true.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

The decision.

 

 

 

Introduction.

 

Let's enter concept of a series.

On a time series elements of one kind are located by congestions. These congestions we shall name series.

A series is a piece on the time series, made of successively located on it L elements of one kind (for example, true, false or other ).

a) “Successively” is the main concept that is a series from elements of the given kind cannot include elements of other kind.

b) A series from elements of the given kind should be limited from both sides or an element of other kind, either the beginning or the end of time series.

The length of a series (L) is defined by quantity of the elements making this series.

a) As it is understandable, the maximal length of a series (Lmax) is equal to total of elements of the kind at all time series of which this series is made.

b) The minimal length of a series (Lmin) is equal to one element of the kind of which this series is made.

Example:

 



        

 

 

 

 

 

 



 



 

 



 

 

 

 



 

an elements

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

The beginning of time series

t

t

t

t

f

f

t

f

f

t

t

f

f

f

t

t

t

t

t

f

The end of time series

n→

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

16

17

18

19

20

 

 



 



 



 

 

 



 

 

    

 

 

 

1. Definition of probability of time series with the data unique (that is the only thing) selection of series true.

 

 

 

Let's define dependence of quantity of series false (F) from quantity of series true (T).

a) The minimum quantity of series false (Fmin) is possible when both in the beginning and at the end of time series there is a series true,

 

The beginning

t

f

t

f

…

t

f

t

The end

 

and as series true and false alternate, in this case series false is less on unit, than series true

Fmin=T−1.

 

b) The maximum quantity of series false (Fmax) is possible when both in the beginning and at the end of time series there is a series false,

 

The beginning

f

t

f

t

…

f

t

f

The end

 

then

Fmax=T+1.

 

c) The quantity of series false is equal to quantity of series true in the event that in the beginning of time series there is a series true, and at the end of time series there is a series false, or on the contrary.

 

The beginning

t

f

t

f

…

f

t

f

The end

f

t

f

t

…

t

f

t

 

Fequ=T.

 

That is

The quantity of series false at the given quantity of series true can be or equal to quantity of series true, or more on unit, or less on unit.

 

Let's define quantity of possible combinations (variations) of series true in n places of time series with the given relative frequency p*, without rearrangements of elements true among themselves.

By definition, well-known in theory of probabilities, quantity of variations of time series (or combinations of series of different lengths in a time series in length n) kall - there is a combination n elements on u elements true (u=p*n-frequency of an element true), that is

 

                                                                     The formula 1.1[I]

 

or in the habitual form of multiplication[II]   

                                  

                                                                                                         The formula 1.2

 

So, we have series of a kind true (TL, where L is a length of a series): T1, T2, T3, …, TLmax. Let the quantity of series of a kind true is equal T, and the quantity of series of a kind false is equal F. Then

The probability of time series with the given unique selection of series true (psingle t) is equal to the relation of quantity of possible combinations of the given unique selection of series TL1, TL2, …, TLi in n places of time series (without rearrangements of series with identical length among themselves) (ksingle t) to quantity of possible combinations of all series T1, T2, T3, …, TL-1, TL in n places of the given time series (kall).

 

                                                                                            The formula 2.

 

The quantity of possible combinations of the given unique selection of series TL1, TL2, …, TLi and one of unique selections of series FL1, FL2, …, FLi (ksingle tf) is equal to multiplication of three multipliers: a) quantity of rearrangements of series true concerning the beginning of time series (Rtf); b) quantity of rearrangements of series true among themselves, without rearrangements of series true identical lengths between themselves (Rt); c) quantity of rearrangements of series false among themselves, without rearrangements of series false identical lengths between themselves (Rf).

 

                                                                                      The formula 3.

 

a)  Rtf - the quantity of rearrangements of sequence of series true concerning the beginning of time series (or concerning sequence of series false), at different combinations of quantity of series true (T) and quantities of series false (F) can be three kinds

1. At T=F, Rtf=2, that is two rearrangements concerning time series

 

The beginning of

time series

f

t

f

t

…

t

f

t

The end of

time series

and

t

f

t

f

…

f

t

f

 

2. At F=T-1, Rtf=1, that is rearrangements of sequence of series true concerning the beginning of time series are not present.

 

The beginning of

time series

t

f

t

f

…

t

f

t

The end of

time series

 

3. At F=T+1, Rtf=1, it is similar to item 2.

 

The beginning of

time series

f

t

f

t

…

f

t

f

The end of

time series

 

b) Rt - quantity of rearrangements of series true among themselves, without rearrangements of series true identical lengths between themselves.

 

,

 

where the numerator is a full quantity of rearrangements of series true among themselves, and a denominator is a quantity of rearrangements of series true identical lengths among themselves (ktL – quantity in the given unique selection of series of identical length L)

 

c) Rf - quantity of rearrangements of series false among themselves, without rearrangements of series false identical lengths between themselves, is similar to item b).

 

.

 

The quantity of possible combinations of the given unique selection of series TL1, TL2, …, TLi  and all unique selections of series FL1, FL2, …, FLi (ksingle t) is equal to the sum ksingle tf for all selections of series FLi:

 

                                                                                          The formula 4.

 

Let's consider an example of a finding ksingle t.

Let n=10, p* = 0.7,

Then u=7, ū =3.

For convenience we shall make the table.

 

1.

The given unique selection of series of a kind true.

2.

Quantity of series true. (T)

3.

Quantity of series false.

(F)

Fequ=T,

Fmax=T+1,

Fmin=T-1.

4.

Possible unique selection of series false.

5.

Rtf

6.

Rt

7.

Rf

8.

Quantity of combinations for unique selection of series false and the given unique selection of series true.

(ksingle tf )

9.



 

T7

(the greatest possible length of a series)

1

Fequ=1

Fmax=2

Fmin=0

F3

F2F1

 Does not exist

2

1

 

1

1

2

 

2

2

 

4

T6T1

2

Fequ=2

Fmax=3

Fmin=1

F2F1

F1F1F1

F3

2

1

1

2

2

1

1

8

2

2

12

T5T2

2

Fequ=2

Fmax=3

Fmin=1

F2F1

F1F1F1

F3

2

1

1

2

2

1

1

8

2

2

12

T5T1T1

3

Fequ=3

Fmax=4*

Fmin=2

F1F1F1

Does not exist F2F1

2

 

1

3

1

 

2

6

 

6

12

T4T3

2

Fequ=2

Fmax=3

Fmin=1

F2F1

F1F1F1

F3

2

1

1

2

2

1

1

8

2

2

12

T4T2T1

3

Fequ=3

Fmax=4*

Fmin=2

F1F1F1

Does not exist F2F1

2

 

1

6

1

 

2

12

 

12

24

T4T1T1T1

4

Fequ=4*

Fmax=5*

Fmin=3

Does not exist Does not exist

F1F1F1

 

 

1

4

 

 

1

 

 

4

4

T3T3T1

3

Fequ=3

Fmax=4*

Fmin=2

F1F1F1

Does not exist F2F1

2

 

1

3

1

 

2

6

 

6

12

T3T2T2

3

Fequ=3

Fmax=4*

Fmin=2

F1F1F1

Does not exist F2F1

2

 

1

3

1

 

2

6

 

6

12

T3T2T1T1

4

Fequ=4*

Fmax=5*

Fmin=3

Does not exist Does not exist

F1F1F1

 

 

1

12

 

 

1

 

 

12

12

T2T2T2T1

4

Fequ=4*

Fmax=5*

Fmin=3

Does not exist Does not exist

F1F1F1

 

 

1

4

 

 

1

 

 

4

4

T2T2T1T1T1

T2T1T1T1T1T1

T1T1T1T1T1T1T1

5

6

7

Fmin=4*

Fmin=5*

Fmin=6*

Does not exist Does not exist

Does not exist

 

 

 

 

Does not exist

 

In total 120

 

The table 1.

 

* Such combinations does not exist, as the minimum quantity of series false is more, than all elements false (ū =3).

 

It is possible to check up the received result, summarizing all ksingle t

 

 (look the formula 1.2).

 

So, having defined ksingle t, kall we can define probability for the given unique selection of series true (p single t, the Formula 2).

 

On the considered example at n=10, p * = 0.7 we shall find probability of the given selection of series true - T5T1T1:

 

,

kall=120           Þ         

 

The probability of the given unique selection of series true - T5T1T1 is equal to ten percent.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

2. Definition of probability of presence (occurrence) of a series true in length L on a time series.

 

 

 

Let's define probability of presence of a series true in length L (ptL).

The probability ptL is equal to the relation of quantity of all series in length L (kL) in all combinations of time series to all series of all lengths (kL all) in all combinations of time series.

 

                                                                                          The formula 5.

 

The quantity of series in length L (kL) can be found with summation of these series in all combinations of time series. The quantity of series of all lengths (kL all) also can be found with summation of all series in all combinations of time series (the formula 5).

Let's consider an example of a finding kL, kL all, ptL.

Let n=10, p * = 0.7

Let's make the table

 

1.

Length of a series.

(L)

2.

Selection of series true with presence (including) series in length L.

3.

Quantity of series in length L in the given selection of series.

4.

Quantity of combinations for the given selection of series true.

5.

Quantity of series in length L in all combinations for the given selection of series true.

(5.=3.´4.)

6.

Quantity of series in length L in all combinations of time series.

(kL)

7

T7

1

4

4

4

6

T6T1

1

12

12

12

5

T5T2

T5T1T1

1

1

12

12

12

12

24

4

T4T3

T4T2T1

T4T1T1T1

1

1

1

12

24

4

12

24

4

40

3

T3T4

T3T3T1

T3T2T2

T3T2T1T1

1

2

1

1

12

12

12

12

12

24

12

12

60

2

T2T5

T2T4T1

T2T3T2

T2T3T1T1

T2T2T2T1

1

1

2

1

3

12

24

12

12

4

12

24

24

12

12

84

1

T1T6

T1T5T1

T1T4T2

T1T4T1T1

T1T3T3

T1T3T2T1

T1T2T2T2

1

2

1

3

1

2

1

12

12

24

4

12

12

4

12

24

24

12

12

24

4

112

 



 

The table 2.

 

Let's find, using table 2, probability of presence of a series true in length L=5.

 

kL=5=24,

kL all=336    Þ    .

 

The probability of presence of a series true in length L=5 is equal 7,14 percent.

 

Let's pay attention, that the column 6 in table 2 is growing sequence of the bivariate sum. The way of decomposition of sequence on summands we shall find regularity between length of a series true (L), quantity of tests (n), relative probability of event true (p*) and quantity of series in length L in all combinations of time series (kL)[III].

 

              The formula 6.1

 

Or in the habitual form of multiplication

 

       The formula 6.2

 

Now, taking into account the formula 6.1 and Lmax=u, we shall open the sum 

 

              The formula 7[IV].

 

Let's express probability of presence of the given series in length L of a kind true (the formula 5) through formulas 6.1 and 7.

 

                              The formula 8.1

 

or in the habitual form of multiplication

 

      

 

The formula 8.2

Special case n→.             

Let's define probability of presence (occurrence) of a series true in length L at unlimitedly growing number of events on a time series. That is we shall find a limit ptL at n→.

 

 

a) Let's open brackets in a numerator

 

 

 

b) Let's open brackets in a denumerator

 



 

Let's divide numerator and a denominator on n the greater degree (nL) and we shall take a limit from numerator and a denominator.

 



 

Or

 

                                                                                          The formula 9.

 

 

Values of probabilities of presence (occurrence) of the given series in length L on a time series for n=10 and for n→ with step p* in 0,1 are resulted in the application 1.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

3. Definition of probability of continuation of a series true (or, that the same, probabilities of continuation of time series with an element true).

 

 

 

Let's define probability of continuation of a series in length L. This probability is probability of continuation of time series with an element true.

The probability of continuation of a series in length L is a probability, that the given series is series L+1 or is higher, that is passes in a series of the biggest lengths.

 

Bright example:

 

A time series

 



 



 

 

 

 

elements

…

false

false

false

true

true

false

true

true

true

…

At present the end of time series

 

 

 

 





 

 

The probability of transition (continuation) of a series in length L in a series in length L+1 (ptL/L+1) is equal to the relation of the sum of probabilities of occurrence of series of lengths L+1, L+2, …, Lmax (that is probabilities of occurrence of series L+1 or is higher) to the sum of probabilities of occurrence of series of lengths L, L+1, L+2, …, Lmax (that is probabilities of occurrence of series L or is higher).

 

                                      The formula 10.

 

Let's consider an example of definition ptL/L+1.

Let n=10, p * = 0.7

Let's make the table

 

1.

Length of a series.

L

2.

Quantity of possible series in length L.

kL

3.

Probability of presence of a series in length L on a time series.

ptL, %

4.

The sum of possible series from length L till length Lmax=u.



5.

Probability of occurrence of a series in length from L up to Lmax=u.

, %

6.

The probability of transition of a series in length L in a series in length is higher, calculated on one of formulas 10.

ptL/L+1

Remained series in length L(Has not proceeded)

Has passed series to series in length L+1 or is higher(Has proceeded)

1

112

33,33

336

100,0

33,33/

/66,66

2

84

25,00

224

66,66

37,50/

/62,50

3

60

17,86

140

41,66

42,86/

/57,14

4

40

11,90

80

23,80

50,00/

/50,00

5

24

7,14

40

11,90

60,00/

/40,00

6

12

3,57

16

4,76

75,00/

/25,00

7

4

1,19

4

1,19

100,0/

/0

 

The table 3.

 

Each given probability in the column 5 means probability of occurrence of a series in length L or is higher. It is evidently visible, that the probability of transition of a series in length L in a series of the greater length is equal to the relation of probability of occurrence of series in the length from L+1 up to Lmax to probability of occurrence of series L up to Lmax, or, that the same, to the relation of the sum of possible series in length from L+1 up to Lmax to the sum of possible series in length from L up to Lmax.

 

Let's express probability of transition (continuation) of a series in length L in a series in length L+1 (ptL/L+1) using formulas 6.1 and 8.1.

Let's find the sum of possible series in length from L up to Lmax

 

,

 

or

 

[V].

 

Then

 

   

 

The formula 11.1

 

Or in the habitual form of multiplication

 

                                                                      The formula 11.2

 

Special case n→.             

Let's define probability of transition (continuation) of a series in length L in a series in length L+1 at unlimitedly growing number of events on a time series, that is we shall find a limit ptL/L+1 at n→.

 

                                                                                  The formula 12[VI].

 

That is at n→ transition (continuation) of a series in length L in a series in length L+1 is equal to relative probability of occurrence of an element true at anyone L. It proves, that at any moment of time series the probability of occurrence of the given outcome is constant (and is equal p*).

Values of probabilities of transition of a series in length L in a series in length L+1 on a time series for n=10 and for n→ with step p* in 0,1 are resulted in the application 1.

 

Consequence. The probability of transition of a series in length L in a series in length L+l also is equal to the relation of the sum of possible series in length from L+l up to Lmax to the sum of possible series in length from L up to Lmax, that is

 

                                                           The formula 13.1

 

Or in the form of multiplication

 

                                The formula 13.2

 

Special case n→.

Let's define probability of transition of a series in length L in a series in length L+l at unlimitedly growing number of events on a time series, that is we shall find a limit ptL/L+l at n→.

 

                                                                                        The formula 14.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

4. The decision of accompanying tasks.

 

 

 

4.a Definition of a population mean and a dispersion of length of a series true.

 

Let's find a population mean of length of a series true M (L).

Let ptL - the probability of occurrence of a series in length L, length of series L belongs to a range [1; Lmax=u]. Then by definition of a population mean

 



[VII]

 

Or

 

                                                                          The formula 15.1

 

In the habitual form of multiplication this formula will be written down

 

                                                             The formula 15.2

 

Special case n→.             

At unlimitedly growing number of events on a time series the population mean of size L is equal to a limit:

 

                                                            The formula 16.

 

Let's find a dispersion of length of a series true D (L).

By definition of a dispersion

 







 

Let's take the sum from each composed member

,

 

a) =

 

[VIII].

 

b) [IX].

 

c) [X].

 

Then, taking into account a), b), c)

 

                          The formula 17.

 

Special case n→.             

At unlimited increase of number of events the dispersion of size L is equal to a limit:

 

                                      The formula 18.

          

The mean square deviation of a dispersion of length of a series true σ (L) is equal



 

Example:

 

 

M(L)

D(L)

σ

n=10

p*=0,7

2,50

2,25

1,50

n→

p*=0,7

3,33

7,77

2,78

 

 

 

4.b Definition of probable quantity of series true.

 

Let's define probable quantity of series true all lengths (Sp) at the given probability of presence of a series true (ptL).

Let's consider a task.

Let the number of events on a time series is equal n, relative frequency of an element true is equal p*. Define, how many series true will appear probably.

The decision.

As u it is equal to the sum of multiplications of lengths of series by quantity of series on the given time series:

, where SpL - quantity of series in length L,

but , where

Sp – probable number of series;

 ptL – probability of occurrence of a series in length L

                          .

 

Then

 

                                                                                       The formula 19.

 

From here

 

                                                                            The formula 20.1[XI]

 

Or in the form of multiplication

 

                                                        The formula 20.2[XII]

                  

Example:

n=10

p*=0,7



 

 

 

4.c Definition of capacity of a series true.

 

Capacity of a series (VL) is the quantitative characteristic of distribution of elements on series of different length. It Defines quantity of elements of the given kind in all series in length L on the given time series.

 

For expected time series

Probable capacity of a series (VLp) is defined by multiplication of probable quantity of series of the given element (Sp), probabilities of presence of a series in length L (ptL) and quantity of elements in the given series in length L (L) that is

 

                                                                                    The formula 22.1

        

Let's transform the given formula, using formulas 20.1 and 8.1

 

                         The formula 22.2

 

Or in the habitual form of multiplication

 

             The formula 22.3

 

 

For the happened time series

The given capacity of a series (VL) is equal to multiplication of the given quantity of series (S), relative quantity of series in length L (prel.=SL/S, where SL is the given quantity of series in length L) and quantity of elements of the given series in length L (L), that is

 

                                                                       The formula 23.1

 

It is frequently more convenient to consider distribution of elements on series concerning quantity of elements, that is in percentage.

Relative capacity of a series (vL) is the relative characteristic of distribution of elements on series of different length. It Defines a percentage part of elements of the given kind in series in length L on the given time series.

 

For expected time series

Probable relative capacity of a series (vLp) is equal to the relation of probable capacity of a series (VLp) to probable quantity of elements (u=np*), that is

 

                                                                The formula 23.2

 

Or in the habitual form of multiplication

 

                  The formula 23.3

 

 

For the happened time series

The given relative capacity of a series (vL) is equal to the relation of the given capacity of a series (VL) to the given quantity of elements (u), that is

 

                                                                                    The formula 24.

 

Special case n→.

Let's find probable relative capacity at unlimitedly growing number of events on a time series, that is we shall find a limit

 

       The formula 25.

 

Example:

 

P*=0,7

Probable capacity of a series true.

VLp, elements

Probable relative capacity of a series true.

vLp, %

L

1

2

3

4

5

6

7

1

2

3

4

5

6

7

n=10

 

 

1,50

 

 

 

 

 

 

21,42

 

 

 

 

 

1,40

 

1,33

 

 

 

 

20,00

 

19,05

 

 

 

0,93

 

 

 

1,00

 

 

13,33

 

 

 

14,28

 

 

 

 

 

 

 

0,60

 

 

 

 

 

 

8,57

 

 

 

 

 

 

 

0,23

 

 

 

 

 

 

3,33

n→



 

 

13,23

 

 

 

 

 

12,60

 

12,35

 

 

 

 

 

 

 

10,80

 

 

9,00

 

 

 

 

9,07

 

 

 

 

 

 

 

7,41

 

The table 4.

 

Under the table we see, that a lot of elements falls at a series in length L=3.

 

Probable maximum of relative capacity.

Let's find a series in length L on which the maximum of elements will have, at unlimitedly growing number of events on a time series, that is we shall find a maximum of function:

The maximum of function is in a point in which the derivative of function does not exist or is equal to zero.

Derivative of function f(L):

 



 

Critical points:



 



 

So,

The length of a series on which it is necessary a maximum of probable relative capacity (Lmax vLp), that is a lot of elements, at unlimitedly growing number of events is defined by the formula:

 

                                                   The formula 26.

 

Probable relative capacities of series in length L for p* with step in 0,1 and length of a series on which it is necessary a maximum of probable relative capacity at n→, are resulted in the application 3.

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

Applications.

 

The application 1.

 

The table of values of probabilities of presence (occurrence) of the given series in length L (ptL - the first column) and values of probabilities of transition of a series in length L into a series in length L+1 (ptL/L+1 - the second column, in percentage) on a time series for n=10 with step p* in 0,1.

 

  p*

L

0,1

0,2

0,3

0,4

0,5

0,6

0,7

0,8

0,9

1

 

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

1

1,0000

0,0

0,8889

11,1

0,7778

22,2

0,6667

33,3

0,5556

44,4

0,4444

55,6

0,3333

66,7

0,2222

77,8

0,1111

88,9

0,0000

100,0

2

 

 

0,1111

0,0

0,1944

12,5

0,2500

25,0

0,2778

37,5

0,2778

50,0

0,2500

62,5

0,1944

75,0

0,1111

87,5

0,0000

100,0

3

 

 

 

 

0,0278

0,0

0,0714

14,3

0,1190

28,6

0,1587

42,9

0,1786

57,1

0,1667

71,4

0,1111

85,7

0,0000

100,0

4

 

 

 

 

 

 

0,0119

0,0

0,0397

16,7

0,0794

33,3

0,1190

50,0

0,1389

66,7

0,1111

83,3

0,0000

100,0

5

 

 

 

 

 

 

 

 

0,0079

0,0

0,0317

20,0

0,0714

40,0

0,1111

60,0

0,1111

80,0

0,0000

100,0

6

 

 

 

 

 

 

 

 

 

 

0,0079

0,0

0,0357

25,0

0,0833

50,0

0,1111

75,0

0,0000

100,0

7

 

 

 

 

 

 

 

 

 

 

 

 

0,0119

0,0

0,0556

33,3

0,1111

66,7

0,0000

100,0

8

 

 

 

 

 

 

 

 

 

 

 

 

 

 

0,0278

0,0

0,1111

50,0

0,0000

100,0

9

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

0,1111

0,0

0,0000

100,0

10

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

0,0000

0,0

 

The table of values of probabilities of presence (occurrence) of the given series in length L≤15 (ptL - the first column) and values of probabilities of transition of a series in length L≤15 into a series in length L+1 (ptL/L+1 - the second column, in percentage) on a time series for n→ with step p* in 0,1.

 

  p*

L

0,1

0,2

0,3

0,4

0,5

0,6

0,7

0,8

0,9

1

 

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

ptL     ptL/L+1

1

0,9000

10

0,8000

20

0,7000

30

0,6000

40

0,5000

50

0,4000

60

0,3000

70

0,2000

80

0,1000

90

0

100

2

0,0900

10

0,1600

20

0,2100

30

0,2400

40

0,2500

50

0,2400

60

0,2100

70

0,1600

80

0,0900

90

0

100

3

0,0090

10

0,0320

20

0,0630

30

0,0960

40

0,1250

50

0,1440

60

0,1470

70

0,1280

80

0,0810

90

0

100

4

0,0009

10

0,0064

20

0,0189

30

0,0384

40

0,0625

50

0,0864

60

0,1029

70

0,1024

80

0,0729

90

0

100

5

0,0001

10

0,0013

20

0,0057

30

0,0154

40

0,0313

50

0,0518

60

0,0720

70

0,0819

80

0,0656

90

0

100

6

0,0000

10

0,0003

20

0,0017

30

0,0061

40

0,0156

50

0,0311

60

0,0504

70

0,0655

80

0,0590

90

0

100

7

0,0000

10

0,0001

20

0,0005

30

0,0025

40

0,0078

50

0,0187

60

0,0353

70

0,0524

80

0,0531

90

0

100

8

0,0000

10

0,0000

20

0,0002

30

0,0010

40

0,0039

50

0,0112

60

0,0247

70

0,0419

80

0,0478

90

0

100

9

0,0000

10

0,0000

20

0,0000

30

0,0004

40

0,0020

50

0,0067

60

0,0173

70

0,0336

80

0,0430

90

0

100

10

0,0000

10

0,0000

20

0,0000

30

0,0002

40

0,0010

50

0,0040

60

0,0121

70

0,0268

80

0,0387

90

0

100

11

0,0000

10

0,0000

20

0,0000

30

0,0001

40

0,0005

50

0,0024

60

0,0085

70

0,0215

80

0,0349

90

0

100

12

0,0000

10

0,0000

20

0,0000

30

0,0000

40

0,0002

50

0,0015

60

0,0059

70

0,0172

80

0,0314

90

0

100

13

0,0000

10

0,0000

20

0,0000

30

0,0000

40

0,0001

50

0,0009

60

0,0042

70

0,0137

80

0,0282

90

0

100

14

0,0000

10

0,0000

20

0,0000

30

0,0000

40

0,0001

50

0,0005

60

0,0029

70

0,0110

80

0,0254

90

0

100

15

0,0000

10

0,0000

20

0,0000

30

0,0000

40

0,0000

50

0,0003

60

0,0020

70

0,0088

80

0,0229

90

0

100

 

The application 2.

 

График зависимости вероятности появления серии длиной L от относительной вероятности появления элемента true при количестве событий, стремящемся к бесконечности, то есть ptL от p* для L при n→

 



Under the schedule

a) Knowing p* it is possible to define the expected percent of series in length L at n→.

b) Knowing ptL it is possible to define expected probability of an outcome (element) at n→.

 

 

The application 3.

 

The table of values probable relative capacities of a series in length L≤20 (vLp) and values of length of a series on which it is necessary a maximum of probable relative capacity (Lmax vLp),

For n→  with step p* in 0,1.

 

Lmax vLp

0,4343

0,6213

0,8306

1,0914

1,4427

1,9576

2,8037

4,4814

9,4912

µ

       P*

    L

0,1

0,2

0,3

0,4

0,5

0,6

0,7

0,8

0,9

1

1

81,0000

64,0000

49,0000

36,0000

25,0000

16,0000

9,0000

4,0000

1,0000

0

2

16,2000

25,6000

29,4000

28,8000

25,0000

19,2000

12,6000

6,4000

1,8000

0

3

2,4300

7,6800

13,2300

17,2800

18,7500

17,2800

13,2300

7,6800

2,4300

0

4

0,3240

2,0480

5,2920

9,2160

12,5000

13,8240

12,3480

8,1920

2,9160

0

5

0,0405

0,5120

1,9845

4,6080

7,8125

10,3680

10,8045

8,1920

3,2805

0

6

0,0049

0,1229

0,7144

2,2118

4,6875

7,4650

9,0758

7,8643

3,5429

0

7

0,0006

0,0287

0,2500

1,0322

2,7344

5,2255

7,4119

7,3400

3,7201

0

8

0,0001

0,0066

0,0857

0,4719

1,5625

3,5832

5,9295

6,7109

3,8264

0

9

0,0000

0,0015

0,0289

0,2123

0,8789

2,4186

4,6695

6,0398

3,8742

0

10

0,0000

0,0003

0,0096

0,0944

0,4883

1,6124

3,6318

5,3687

3,8742

0

11

0,0000

0,0001

0,0032

0,0415

0,2686

1,0642

2,7965

4,7245

3,8355

0

12

0,0000

0,0000

0,0010

0,0181

0,1465

0,6966

2,1355

4,1232

3,7657

0

13

0,0000

0,0000

0,0003

0,0079

0,0793

0,4528

1,6194

3,5734

3,6716

0

14

0,0000

0,0000

0,0001

0,0034

0,0427

0,2926

1,2208

3,0786

3,5586

0

15

0,0000

0,0000

0,0000

0,0014

0,0229

0,1881

0,9156

2,6388

3,4315

0

16

0,0000

0,0000

0,0000

0,0006

0,0122

0,1204

0,6836

2,2518

3,2943

0

17

0,0000

0,0000

0,0000

0,0003

0,0065

0,0767

0,5085

1,9140

3,1501

0

18

0,0000

0,0000

0,0000

0,0001

0,0034

0,0487

0,3769

1,6213

3,0019

0

19

0,0000

0,0000

0,0000

0,0000

0,0018

0,0309

0,2785

1,3691

2,8518

0

20

0,0000

0,0000

0,0000

0,0000

0,0010

0,0195

0,2052

1,1529

2,7017

0

 

 

The application 4.

 

Actions with multivariate numbers of a sum from unit.

 

1{x;y}=

2 By definition of multivariate number of a sum from unit



 

3 Disclosing of the sum of multiplications of bivariate numbers at consistently varying first coordinates 

4 Disclosing complex function



 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

It is necessary to finish.

 

    To add comments.

2. An example of decomposition kL.

3. To prove, that ptL, ptL/L+l, M(L), D(L),Sp, vLp, Lmax vLp at n→ for events with outcomes quantity more than two coincide with values for events with two outcomes.

4.b Allowable limits of use of the formula 21.

4.c the Maximum of relative capacity of a series for the limited time series.

5. vLp at Lmax vLp , the schedule.

6. Points 1-4 for continuous time line ().

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

Table of contents.

 

 

The task.

The analysis of the task.

The decision.

Introduction.

1. Definition of probability of time series with the data unique (that is the only thing) selection of series true.

2. Definition of probability of presence (occurrence) of a series true in length L on a time series.

3. Definition of probability of continuation of a series true (or, that the same, probabilities of continuation of time series with an element true).

4. The decision of accompanying tasks.

4.a Definition of a population mean and a dispersion of length of a series true.

4.b Definition of probable quantity of series true.

4.c Definition of capacity of a series true.

Applications.

It is necessary to finish.

 

 

 

 

 

 

 

 

 

 

 

 

 


[I] Number with coordinates {x; y} there is a bidimentional number of a sum from unit:  (read “the Theory of multivariate numbers ”).

[II] The application 4-1.

 

[III] About sequence of the bidimentional sum and the way of decomposition of sequence on summands read in “ the Theory of multivariate numbers ”.

[IV] The application 4-2. All actions with multivariate numbers are proved in “ the Theory of multivariate numbers ”.

 

[V] The application 4-2.

[VI] Experience speaks, that ptL, ptL/L+l, M(L), D(L),Sp, vLp, Lmax vLp at n→ for events with outcomes quantity more than two coincide with values for events with two outcomes.

[VII] The application 4-3.

[VIII] The application 4-4.

[IX] The application 4-3.

[X] The application 4-2.

[XI] It is noticed: .

[XII] Return finding p* if has taken place S series in n events probably though such way is too inexact.


 

         (The formula 21).
