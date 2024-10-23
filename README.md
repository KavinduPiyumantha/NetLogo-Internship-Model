# Agent-Based Model of Internship Availability for IT Undergraduates

This repository contains a NetLogo-based agent-based model that simulates internship availability for IT undergraduates in Sri Lanka. The model involves different stakeholders, including students, universities, companies, and policymakers, to analyze factors impacting internship opportunities and to test various interventions.

## Overview

This model aims to simulate the availability of internships for IT students, focusing on key dynamics such as:

- Industry and university collaboration
- Economic constraints affecting internship opportunities
- Skill alignment between students and industry needs

The main agents in this simulation are:

- **Students**: Represent IT undergraduates seeking internships, categorized by grade and university type (government or private).
- **Companies**: Represent IT companies of different sizes (Large, Medium, Small) with varying internship capacities and willingness to mentor.
- **Universities**: Represent either government or private institutions.
- **Policymakers**: Represent government authorities intervening to support internship programs, especially during poor economic conditions.

The simulation runs iteratively to represent interactions between students, companies, universities, and policymakers, analyzing the outcome on internship availability.

## Features

- **Agent-Based Approach**: Uses different agent breeds to simulate realistic interactions between stakeholders.
- **Customizable Parameters**: Sliders are available to adjust economic conditions, company sizes, number of students, and other critical factors to see how these affect internship opportunities.
- **Patch Areas**: Specific patch areas are defined for each group of agents for improved visualization and agent interaction management.

## Installation

To run this model, you need NetLogo installed on your computer. You can download NetLogo from [NetLogo's official website](https://ccl.northwestern.edu/netlogo/).

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/netlogo-internship-model.git
   ```
2. Open the `.nlogo` file in the NetLogo application.

## Usage

1. Open the NetLogo model file in NetLogo.
2. Use the **Setup** button to initialize the environment.
3. Press **Go** to run the simulation.
4. Use sliders to adjust key parameters like economic condition, total students, and company capacity to observe how these factors impact internship availability.

## Agents and Interactions

- **Students**: Apply to companies based on availability and preferences.
- **Companies**: Accept students based on internship capacity and willingness to mentor.
- **Policymakers**: Adjust internship capacities based on the economic situation.

Each agent group is positioned in different patch areas:

- Yellow for universities
- Blue for companies
- Green for students
- Red for policymakers

## Model Limitations

- **Initial Version**: This is a foundational version, and more modifications are needed for refining agent interactions, adding real-world complexity, and testing additional scenarios.
- **Simplified Dynamics**: Skill mismatches and curriculum-specific collaborations are simplified.

## Contribution

We welcome collaboration! To contribute:

1. Fork this repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

Please ensure your code follows best practices and is well-documented.

## Future Work

- **Skill Alignment Improvements**: Incorporate detailed skills matching between students and industry needs.
- **Policy Impact Analysis**: Add scenarios to assess the long-term impact of different policies.
- **Industry-University Collaboration**: Simulate collaboration models and their impact on internships.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to contact [[your-email@example.com](mailto:your-email@example.com)].
