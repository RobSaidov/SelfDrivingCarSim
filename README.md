# Self-Driving Car Simulator 🚗💨

A simulation system designed to model the behavior of autonomous vehicles. This project leverages cutting-edge technologies in computer vision, deep learning, and reinforcement learning to enable self-driving cars to navigate virtual environments with lane detection, obstacle avoidance, and path planning.

## Features 🌟

- **Lane Detection:** Uses computer vision to detect and follow lanes.
- **Obstacle Avoidance:** Real-time depth sensing for detecting and avoiding obstacles.
- **Path Planning:** Implements A* and Dijkstra algorithms for efficient route navigation.
- **Reinforcement Learning:** Integrates Q-learning and policy gradients for adaptive driving strategies.
- **Customizable Scenarios:** Simulate various driving environments with CARLA simulator.
- **Deep Learning:** CNNs for object detection and behavior prediction.

---

## Technologies Used 🛠️

- **CARLA Simulator:** For creating virtual driving environments.
- **Python:** Core programming language.
- **OpenCV:** For computer vision tasks like lane detection.
- **TensorFlow/PyTorch:** For deep learning and reinforcement learning.
- **NumPy & Pandas:** For data manipulation and analysis.
- **A* and Dijkstra Algorithms:** For pathfinding.
- **Reinforcement Learning:** Q-learning and policy gradient methods.

---

## Installation ⚙️

1. Clone the repository:
   ```bash
   git clone https://github.com/RobSaidov/SelfDrivingCarSim.git
   cd SelfDrivingCarSim
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download and install the [CARLA Simulator](https://carla.org/):
   - Follow the installation instructions on the official CARLA website.

4. Run the simulator:
   ```bash
   python run_simulation.py
   ```

---

## Usage 🚀

1. Launch the CARLA simulator.
2. Run the `run_simulation.py` script to start the self-driving car.
3. Modify parameters in the `config.json` file to customize scenarios (e.g., weather, traffic, environment).
4. Monitor logs and performance metrics during the simulation.

---

## File Structure 📁

```
SelfDrivingCarSim/
│
├── data/                     # Training and test datasets
├── models/                   # Pre-trained and custom-trained models
├── scripts/
│   ├── lane_detection.py     # Lane detection logic
│   ├── obstacle_avoidance.py # Obstacle avoidance system
│   ├── path_planning.py      # Path planning algorithms
│   ├── reinforcement_learning.py # RL algorithms
│   └── run_simulation.py     # Main simulation script
│
├── config.json               # Configuration file for simulation
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## Example Output 📊

- **Lane Detection:**  
![Lane Detection Example](./assets/lane_detection_example.png)

- **Obstacle Avoidance:**  
![Obstacle Avoidance Example](./assets/obstacle_avoidance_example.png)

- **Path Planning Visualization:**  
![Path Planning Example](./assets/path_planning_example.png)

---

## Contributing 🤝

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## Future Improvements 🔮

- Add support for multi-agent scenarios.
- Implement advanced deep reinforcement learning techniques.
- Integrate real-world driving datasets for more realistic training.

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Contact 📬

Developed by **Rob Saidov**.  
Feel free to reach out for questions or collaboration opportunities!

- **Email:** [robsaidov@gmail.com](mailto:robsaidov@gmail.com)
- **LinkedIn:** [linkedin.com/in/robsaidov](https://linkedin.com/in/robsaidov)
