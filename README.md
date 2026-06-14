# neuromorphic-simulator
Here, I designed event drive smart home assistant-a low power neuromorphic system that reacts only to important environmental changes instead of continuously processing data.
This code is a web-based simulation of a smart fire alarm system that thinks like a human brain cell (neuromorphic computing).Instead of sending your data to the cloud or constantly wasting battery, it processes everything locally using a simulated brain cell (a neuron).
How It Works:
The Sensors (Inputs): You can click buttons to simulate real-world hardware sensors detecting Humidity, Smoke, or Fire.
The Brain Cell Core: When you click a sensor, it injects electrical voltage into the neuron. If nothing happens for a while, the voltage slowly "leaks" away (the system naturally forgets minor fluctuations so it doesn't trigger a false alarm).
Pattern Recognition: If you click "Smoke" and then immediately click "Fire," the system realizes they are connected. It temporarily boosts its sensitivity, realizing a major emergency is happening.
The Siren (Output): If the voltage hits its maximum limit (1.0V), the neuron fires. The screen flashes a bright red warning, and your computer speakers will automatically play a sharp, synthesized hardware alarm siren for 2 seconds.
