# Optimize the Path of Food Delivery

## Authors
- **Han-Wen Liu**
- **Han-Lin Chen**
- **Tien-Yun Kuo**

## Institution
Department of Mechanical Engineering, National Taiwan University, Taipei, Taiwan

---

## **Overview**
Food delivery has become an essential part of modern life in Taiwan, especially with platforms like Uber Eats and Foodpanda. This project focuses on optimizing the delivery process to maximize income for delivery personnel while ensuring that constraints like food quality and delivery time are met.

The report leverages optimization techniques, specifically Genetic Algorithms (GA), to model, simulate, and solve the challenges faced by delivery personnel, providing data-driven strategies to increase efficiency and earnings.

---

## **Project Highlights**
- **Objective**: 
  - Maximize delivery income while adhering to constraints, including:
    - Time limits for entire delivery sequences.
    - Food quality constraints (limit time food stays on delivery vehicle).

- **Methodology**:  
  - **Model Development**:  
    - Simulated delivery scenarios on a 2D grid map with randomized customer and restaurant locations.
    - Assumed simplified real-world constraints, such as constant velocity and no competition between delivery personnel.
  - **Optimization Approach**:  
    - Designed objective functions to maximize income, factoring in:
      - Pickup fees.
      - Delivery fees.
      - Distance fees.
      - Bonuses for completed orders.
    - Applied Genetic Algorithms to find optimal delivery sequences while accommodating constraints.
  - **Simulation and Validation**:  
    - Tested the optimized function across 1,000 randomly generated scenarios using Monte Carlo analysis to evaluate robustness and generalizability.

---

## **Key Results**
- Successfully developed an optimization model that outperforms human decision-making in simulated delivery scenarios.
- Demonstrated that the optimized function:
  - Maintains constraints for 95% of scenarios.
  - Maximizes income while minimizing food stay time.
- Highlighted areas where real-world complexities, like competition and traffic, can impact outcomes.

---

## **Challenges**
- Simplified assumptions, such as a single delivery person and uniform traffic, differ from real-world conditions, particularly in busy areas like Taipei.
- High variability in map configurations introduces uncertainty, requiring robust optimization techniques like GA and Monte Carlo analysis.

---

## **Acknowledgments**
The authors express their gratitude to their course instructor for their invaluable guidance and support throughout this project.

---

## **References**
- External Reference: [Uber Eats Driver Strategies](https://forum.gamer.com.tw/C.php?bsn=60561&snA=14326)

---

For further details, please refer to the full project report or explore the [source code on GitHub](https://github.com/hanlinchentw).
