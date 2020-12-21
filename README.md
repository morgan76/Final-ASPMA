# Final-ASPMA
Final exam of the Audio Signal Processing for Musical Applications class, Music Technology Group, Pompeu Fabra University. 
The goal was to improve the fundamental frequency (f0) detection algorithm provided in the sms-tools package. 
The method implemented relies on a Look Up Table to find harmonic relationships between frequency components of a given signal. A list of possible f0 candidates is then created. Each candidate is weighted according to its frequency magnitude. Finally, the most probable candidate is choosen for each frame. Additionally, a post-processing step is applied to smooth the f0 track throughout the audio extract. 
