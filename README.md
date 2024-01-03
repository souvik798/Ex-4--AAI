<H3>ENTER YOUR NAME</H3>
<H3>ENTER YOUR REGISTER NO.</H3>
<H3>EX. NO.4</H3>
<H3>DATE:</H3>
<H1 ALIGN =CENTER> Implementation of Hidden Markov Model</H1>

## Aim: 
Construct a Python code to find the sequence of hidden states by the known sequence of observances using Hidden Markov Model. Consider two hidden states Sunny and Rainy with observable states,happy and sad.<BR>

## Algorithm:
    Step 1:Define the transition matrix, which specifies the probability of transitioning from  one hidden state to another.<BR>
    Step 2:Define the emission matrix, which specifies the probability of observing each possible observation given each hidden state.<BR>
    Step 3:Define the initial probabilities, which specify the probability of starting in each possible hidden state.<BR>
    Step 4:Define the observed sequence, which is the sequence of observations need to  be analyzed.<BR>
    Step 5:Initialize the alpha matrix with zeros, where each row represents a time    step and each column represents a possible hidden state.<BR>
    Step 6:Calculate the first row of the alpha matrix by multiplying the initial  probabilities by the emission probabilities for the first observation.<BR>
    Step 7:Loop through the rest of the observed sequence and calculate the rest of the alpha matrix by multiplying the emission probabilities by the sum of the product of the previous row of the alpha matrix and the corresponding row of the transition matrix.<BR>
    Step 8:Calculate the probability of the observed sequence by summing the last row of the alpha matrix.<BR>
    Step 9:Find the most likely sequence of hidden states by selecting the hidden state with the highest probability at each time step based on the alpha matrix.<BR>

## Program:
Insert your Program here

## Output:
Show your results here

## Result:
Thus Hidden Markov Model is implemented using python.

