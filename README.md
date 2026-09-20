# Hospital Patient Flow Simulation

A discrete-event simulation project for studying patient flow through a hospital surgical system.

The model represents patients moving through **preparation rooms, an operating room, and recovery rooms**, with limited resource capacities and stochastic arrival and service times. It also captures operating-room blocking when a patient cannot immediately move to recovery.

The project develops the simulation in stages, from conceptual modelling and implementation to statistical experimentation, experimental design, and metamodelling.

## Project Components

- **Conceptual Model** — event-based representation of the healthcare process, system states, events, resources, and performance measures.
- **Simulation Implementation** — discrete-event implementation of the hospital patient-flow model using SimPy.
- **Simulation Experiments** — statistical experiments comparing system configurations using multiple replications, confidence intervals, common random numbers, and alternative service-time distributions.
- **Experimental Design** — serial-correlation analysis, fractional factorial experiments, and regression-based metamodelling to investigate factors affecting system performance.
- **Simulation Paradigms** — an accompanying discussion of discrete-event simulation and agent-based modelling.

## Performance Measures

The analyses consider measures such as patient queue length, throughput time, operating-room utilization and blocking, recovery-room congestion, and preparation-room utilization.

## Technologies

Python, SimPy, NumPy, pandas, Matplotlib, SciPy, statsmodels, and seaborn.

## Running the Notebooks

Install the dependencies with:

```bash
pip install -r requirements.txt
```

Then open the Jupyter notebooks in their respective project folders and run the cells in order.
