### Procedure

- The LP residual signal used as excitation, there are large error values at regular intervals within voiced regions of speech. These are the instants of glottal closure at which the vocal tract system is excited. Hence the LP residual signal can be approximated to the excitation source signal.

- Resynthesis of the speech signal using the LP residual (excitation source) and the LPCs (vocal tract system) gives back the original speech signal. But the synthesized waveform doesn't exactly corresponds to original speech signal waveform. This is because of the different orders of LP analysis used to generate residual signal and synthesize speech signal.

- The excitation source signal can be approximated by a train of impulses, but the quality of synthesized speech is poor though the message can be inferred easily.

- The resynthesised speech signal sounds like a whispered speech when a random noise signal is used as the excitation source.

- It can be seen that an LP order of as low as 3 can capture significant information on the message front even when an impulse train or random noise is used as the excitation. The quality of speech improves with the increase in the LP order. But using the original LP residual signal gives very good synthesis even for the 3rd order LP coefficients.



