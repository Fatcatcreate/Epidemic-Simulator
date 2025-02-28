# Epidemic Simulation

A simple epidemic simulation built using HTML, CSS, and JavaScript. It visualizes the spread of an infection among a population with adjustable parameters such as infection rate, mortality rate, and recovery time.

## Features
- Click on up to 3 cells to infect them at the start.
- Adjust simulation parameters before starting:
  - **Population**: Total number of individuals.
  - **R Rate**: Infection spread probability.
  - **Mortality Rate**: Probability of an infected individual dying.
  - **Recovery Generations**: Time taken for an individual to recover.
- Once started, settings are locked until the simulation ends.
- Individuals who recover become immune (cannot be reinfected).
- The simulation stops when the infection cannot spread for 2 generations.
- A slider allows you to review past generations.

## Controls
- **Click on up to 3 cells** to start the infection.
- **Start Simulation**: Begins the epidemic spread.
- **Restart Simulation**: Resets the grid and allows new settings.
- **Slider**: Navigate through past generations to observe the epidemic trend.

## How to Run
Simply open `gitinfected.html` in a web browser.

## Notes
- The mortality rate is higher than expected; adjust it carefully.
- Inspired by various epidemic modeling approaches.

