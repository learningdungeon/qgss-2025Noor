⚛️ GHZ State on Real IBM Quantum Hardware

Today I executed a 3-qubit GHZ state circuit on real quantum hardware IBM’s Qiskit Runtime!
This experiment was part of the Qiskit Global Summer School 2025 – Lab 0 Bonus Challenge.

💡 What I did:

* Designed a GHZ state using Hadamard + CNOT gates
* Transpiled the circuit to respect real-device coupling constraints
* Used `QiskitRuntimeService` to run it on a live backend (selected via `least_busy`)
* Visualized noisy output using `plot_histogram`

📊 What I observed:

* The ideal GHZ states `000` and `111` appeared as expected
* But also saw noisy states, reminding me of the real-world quantum challenges
* This taught me how decoherence and hardware limitations impact results — things simulators often hide.

🧠 **What I learned:**

* Mapping and transpilation aren’t just optional — they’re essential for real devices.
* Error mitigation will be a key topic in upcoming labs, and I’m excited to explore it further!

