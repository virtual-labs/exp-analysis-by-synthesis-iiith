### Assignment

1. Write a program (C/Matlab/Octave/Scilab) to separate the source and system of a given speech signal of 1 to 2 seconds using short-time LP analysis. Use a window size of 20 ms, a window shift of 10 ms, an LP order of 10. Plot the original signal and the LP residual signal.

2. Write a program (C/Matlab/Octave/Scilab) to resynthesize the speech signal given the sequence of LPCs and the following excitation signals:

   - LP residual derived by using a specified LP order
   - Train of unit impulses with a constant pitch of 10 ms.
   - Train of impulses with the gain varying proportional to the LP residual signal
   - White Gaussian random noise sequence with and without the gain of the LP residual signal imposed.


