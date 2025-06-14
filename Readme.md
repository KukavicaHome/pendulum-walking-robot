Pendulum-Based Walking Robot Simulation (Built from the Couch) Overview 

This project is a minimalist yet powerful 2D walking robot simulator, created entirely in Google Colab using only matplotlib and Python's math libraries. It simulates a human-like bipedal robot that walks across the X-axis using alternating pendulum dynamics for arms and legs.

The simulation is not a copy of academic papers or industry software, but a product of pure mechanical intuition, shaped over decades of hands-on experience — and built today from the comfort of a couch, using only a Galaxy A20 smartphone and the cloud.

Motivation 

"I used to work on VMS systems 40 years ago when 100KB of RAM was a luxury. Back then, if someone showed this robot simulation, it would've been a PhD thesis."
— Creator's Reflection

This project bridges the gap between the golden days of bare-metal computing and modern cloud-based development. It shows that the true power of engineering lies not in resources but in insight.

Features Pendulum-inspired walking with synchronized arm-leg swing Dynamic body shift over support foot Real-time animation in Google Colab using FuncAnimation All calculations based on geometry and basic trigonometry Designed for educational, experimental, and inspirational purposes Technical Highlights Python Matplotlib No physics engine or simulation framework Runs fully in-browser (Colab) How It Works Each step consists of a sinusoidal motion representing a pendulum swing Right leg and right arm swing forward while the left side anchors Then the left swings, the right anchors The torso shifts forward after each swing to simulate balance Arms have refined elbow angles to resemble human motion Run It Yourself 

Open this notebook in Google Colab:

[LINK TO NOTEBOOK HERE] Author's Note 

"Even without fancy tools, what I did on VAX and VMS in labs decades ago — I can now do again, using only the cloud and a mobile phone. I want people to see: you don't need millions, you need vision."

This simulation is a tribute to the engineer's mind that keeps creating, no matter the decade or the device. Built from the couch, with curiosity as fuel.

Future Work Terrain adaptation (stairs, slopes) Balance correction and inverse kinematics Real-time input or sensor integration Export as interactive visualization or game physics base 

Made from Bosnia. Made for the world. Shared with everyone.

