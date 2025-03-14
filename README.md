# Acoustic-Feedback-Suppression
adaptive acoustic feedback cancellation, howling suppression, AI noise reduction, low latency

With the rise of new energy vehicles (NEVs), in-car entertainment systems have become increasingly sophisticated, and vehicle-mounted karaoke systems are now standard in many NEVs. One significant challenge for karaoke systems is acoustic feedback (howling), caused by the close proximity of microphones and car speakers. Traditional feedback suppression algorithms, originally designed for front-rear passenger communication, must now address this issue in karaoke systems. Below is an analysis of key problems to be solved by algorithms in the in-car acoustic environment:

# High-Gain Feedback Suppression
Since drivers cannot hold microphones to communicate with rear passengers, in-car microphones are often positioned far from the driver. Ensuring the driver’s voice is amplified requires high feedback-suppressed acoustic gain, typically demanding a steady-state acoustic gain (ASG) exceeding 12 dB for adequate in-car sound reinforcement. Traditional feedback suppression methods like frequency shifting or notch filtering achieve only 2–5 dB of acoustic gain, making them unsuitable for vehicle systems. Adaptive Feedback Cancellation (AFC) algorithms, however, can boost acoustic gain to 10–12 dB by dynamically canceling feedback signals in real time. Additionally, high-fidelity requirements for karaoke systems demand minimal distortion from feedback suppression.

# Long-Range Uniform Coverage
To achieve comprehensive coverage of the driver’s area, Automatic Gain Control (AGC) algorithms are employed to enhance microphone pickup range. AGC dynamically adjusts volume based on the driver’s vocal intensity, ensuring clear and stable sound reinforcement regardless of speaking volume.

# AI Deep Learning Noise Reduction
To prevent amplification of ambient noise (e.g., HVAC systems, tire noise, or mechanical vibrations) by the sound system, AI-powered noise reduction technology is utilized. This suppresses both steady-state (e.g., AC hum) and non-steady-state (e.g., road noise, knocks) noise, preserving speech clarity and user experience.

# Adaptive Deployment
Vehicle-specific acoustic variations complicate traditional calibration processes. Leveraging robust adaptive algorithms, the system auto-configures to diverse cabin acoustic environments, enabling plug-and-play functionality and significantly reducing setup complexity.

# Algorithm Implementation
A hybrid approach combining AFC, AGC, and AI noise reduction achieves 15–18 dB of acoustic gain while maintaining high fidelity and low latency. This addresses the challenges of in-car sound reinforcement in complex acoustic environments.
Demo available for testing
# (WeChat: Reid1001).
