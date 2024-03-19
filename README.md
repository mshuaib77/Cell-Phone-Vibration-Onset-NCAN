# Cell Phone Vibration Onset NCAN
 Me and my UAlbany ECE teammates were asked design a low latency high precision device to detect the vibration of a cell phone within 5ms precision. the onset of this vibration is compared with the detection of the vibration in the brain, which is detected using an EEG headset.

We went through different vibration sensors and implemented different devices For testing in the MATLAB script, I’m analyzing vibrations detected by a piezoelectric sensor used to monitor cell phone vibrations. I first visualize the signal and a corresponding TTL input to understand their patterns. I then determine the points where the signal starts to rise sharply (onsets) by setting a threshold. To compare the timing of these onsets with the TTL input, I calculate latency and jitter, which helps me understand any delays and variability. I also convert the sample indices to time in milliseconds for a more intuitive grasp of the timing. Lastly, I plot the signal and mark the onset points, giving me a clear visual representation of when the sensor detects the vibrations in relation to the TTL input events.


