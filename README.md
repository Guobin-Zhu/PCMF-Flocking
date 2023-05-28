# PCMF-Flocking
## About the Project

A predictive flocking control framework with Mean field approximation. The flocking control strategy, characterized by rapid response, efficient calculation and excellent control effect, is suitable for complex static and dynamic environment. This platform has also integrated [Vásárhelyi](https://www.science.org/doi/10.1126/scirobotics.aat3536)   and [Olfati-saber](https://ieeexplore.ieee.org/abstract/document/1605401) algorithms to demonstrate the efficiency of the PCMF algorithm.

## Requirements
* Only [MATLAB R2021b](https://www.mathworks.com/support/install-matlab.html?q=&page=1) or later is recommended.

## Getting Started
### Installation

1. Clone the repo or download it directly:
<pre><code> git clone https://github.com/Guobin-Zhu/PCMF-Flocking.git </code></pre>

### A Step-by-step Example of Swarm-RAL
#### Siumulation with No GUI
1. Open MATLAB, enter the workspace of Swarm-RAL.
2. Open <pre><code> swarm_example.m </code></pre> and click "run" or run the following command in command window:
<pre><code> run("./examples/swarm_example.m")</code></pre>
3. One can see two Windows, the left side shows the motion trajectory, the right side shows the agent's state and turn algorithm parameters in <pre><code> param_swarm.m, param_sim.m </code></pre>.

#### Simulation with GUI
1. Open MATLAB, enter the workspace of Swarm-RAL.
2. Open <pre><code> GUI_main.m </code></pre> and click "run" or run the following command in command window:
<pre><code> run("./examples/GUI_main.m")</code></pre>
3. One can see a graphical user interface, click "start simulation" after setting some simulation options. Then the same simulation window can be got.

#### Simulation Analysis
1. After each run, a folder containing some simple charts and data will be saved in <pre><code> results_swarm </code></pre> folder, which named by <pre><code> year_month_day_hour_minute_second </code></pre> format.
2. Run <pre><code> simulation_plot </code></pre>, one can get mre embellished charts.

## Troubleshooting
Please open an [Issue](https://github.com/micros-uav/CoFlyers/issues) if you have some droubles and advice.

The document is being continuously updated.
