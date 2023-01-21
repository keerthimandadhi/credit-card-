# credit-card-
# credit card fraud detection algorithm 1 code
l: length of T
Genuine= [];
Fraud= [];
For i in range 0 to l-w+1:
T: [];
/* sliding window features*/
For j in range i+w-1:
/*Add the transaction to window */
T=T+tj
id;
End
/* features extraction related to amount */
ai1=MAX_AMT(Ti);
ai2=MIN_AMT(Ti);
ai3=AVG_AMT(Ti);
ai4=AMT(Ti);
For j in range i+w-1:
/* Time elapse */
xi= Time(tj)-Time(tj-1)
End
Xi= (ai1, ai2,ai3,ai4,ai5,);
Y= LABEL(Ti);
/* classifying a transaction into fraud or not */
if Yi=0 then
Genuine =Genuine U Xi;
Else
Fraud =Fraud U Xi;
End
# credit card fraud detection algorithm 2 code
T: current transaction with w-1 transaction from window.
C: represents the classifier
Label: true value of the incoming/current transaction.
K: total of transactions processed by model.
If the predicted value ≠ label and label==0 then,
For i in range (0, K):
If the predicted value ≠ label then,
rsi= rsi-1;
Else
rsi =rsi+1;
End
