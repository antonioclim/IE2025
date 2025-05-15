# Conference Presentation: Addressing Technical Debt Through Scenario-Based Development (SBD): A Cost-Driven Approach

---

## Slide 1: ADDRESSING TECHNICAL DEBT (TD) THROUGH SCENARIO-BASED DEVELOPMENT (SBD)
- **Authors:** Antonio Clim, Radu Constantinescu, Sabina Amaricai  
- **Affiliations:** Academy of Economic Studies, Bucharest & Bridge in Tech, Dublin  

**Speaker Notes:**  
"Good [morning/afternoon], everyone. Today, I'll explain how we use Scenario-Based Development, or SBD, combined with clear cost metrics, to effectively manage Technical Debt in software projects."

---

## Slide 2: INTRODUCTION TO TECHNICAL DEBT (TD)
- **Definition:** Short-term coding shortcuts causing future extra maintenance work.
- **Impact:** Lower software quality, reduced team productivity, higher future costs.

**Speaker Notes:**  
"Technical Debt happens when development teams take shortcuts to deliver software faster. These shortcuts seem helpful at first but later cause extra work, higher costs, and quality problems."

---

## Slide 3: RESEARCH OBJECTIVES
- Identify communication and organizational challenges.
- Develop simple and effective ways to measure Technical Debt.
- Propose Scenario-Based Development (SBD) as a practical solution.

**Speaker Notes:**  
"Our research focuses on understanding why teams struggle with Technical Debt, creating simple metrics to measure its impact, and showing how SBD helps teams manage this debt effectively."

---

## Slide 4: OBSERVED CHALLENGES
- Conflicts among team members: developers, managers, architects.
- Missing clear methods to evaluate and discuss Technical Debt.
- Results: confusion, frustration, higher costs, poorer software quality.

**Speaker Notes:**  
"We found that teams struggle because different roles—like developers, managers, and architects—have different priorities and lack clear ways to talk about Technical Debt. This confusion leads to increased costs and decreased software quality."

---

## Slide 5: SCENARIO-BASED DEVELOPMENT (SBD) as solution
- Linking real-world user scenarios to measurable Technical Debt outcomes.
- **Elements:** Scenarios, Actors, Actions, Goals.

**Speaker Notes:**  
"Scenario-Based Development helps teams clearly connect user needs to specific Technical Debt tasks. It provides a common language everyone understands, making decisions about debt easier and clearer."

---

## Slide 6: SCENARIO-BASED DEVELOPMENT (SBD) figure
- Visual connection between scenarios and specific Technical Debt items.

**Speaker Notes:**  
"This diagram visually shows how each user scenario is directly linked with specific Technical Debt items, helping teams prioritize and discuss clearly."

---

## Slide 7: Cost-Driven FRAMEWORK Overview (Part 1/2)
- **Basic Metrics Explained:**
  - **Story Cost:** Basic effort for a new feature.
  - **TD Cost:** Effort to fix a specific Technical Debt issue before adding new features.
  - **Story Cost with TD fix:** Effort needed when fixing the debt and adding a feature together.

**Speaker Notes:**  
"We use simple metrics based on the Fibonacci scale, common in Agile teams, to measure effort. Story Cost represents basic effort, while TD Cost measures the effort to fix debt separately."

---

## Slide 8: Cost-Driven FRAMEWORK Overview (Part 2/2)
- **Additional Metrics Explained:**
  - **Story Cost if TD previously solved:** Effort if Technical Debt was fixed earlier.
  - **Interest:** Extra future effort if Technical Debt is not fixed now.
- Simple process steps for decision-making.

**Speaker Notes:**  
"We also consider what the cost would be if debt was already solved earlier, reducing current effort. 'Interest' represents extra future effort incurred by delaying Technical Debt fixes."

---

## Slide 9: Practical Example – Login Scenario
- Fixing insufficient unit test coverage for login features.
- Clear benefits of immediate Technical Debt resolution.

**Speaker Notes:**  
"Here's a clear example: adding a login feature. Fixing unit testing debt immediately provides clear and immediate cost savings, shown by simple Fibonacci-based estimates."

---

## Slide 10: Case Study – Fintech Database Integration (Part 1/3)
- Real-world context: changing databases with existing debt (poor design, insufficient testing).
- Practical use of our framework.

**Speaker Notes:**  
"We applied our framework to a fintech project changing their database, effectively identifying and addressing Technical Debt issues like poor design and inadequate testing."

---

## Slide 11: Case Study – Fintech Database Integration (Part 2/3)
- Improved planning accuracy and fewer software defects.

**Speaker Notes:**  
"Using our framework significantly improved planning accuracy and reduced software defects, demonstrating clear benefits from managing Technical Debt early."

---

## Slide 12: Further Results – Highlights
- 50% less effort in future database integrations.
- 12% higher productivity, 23% fewer defects.
- Improved team happiness and alignment by 16%.

**Speaker Notes:**  
"Additional benefits included reduced future task complexity, increased productivity, significantly fewer defects, and notably better team satisfaction and alignment."

---

## Slide 13: Case Study – Fintech Database Integration (Part 3/3)
- Enhancements in software automation for better scalability.

**Speaker Notes:**  
"The project benefited greatly from improved automation, enhancing software scalability and maintainability for future needs."

---

## Slide 14: Summary of RESEARCH QUESTIONS answered
- Clearly identified reasons for Technical Debt struggles.
- Developed practical metrics to measure Technical Debt impacts.
- Demonstrated Scenario-Based Development’s real-world effectiveness.

**Speaker Notes:**  
"Our research clarified team challenges, developed straightforward metrics, and validated Scenario-Based Development as a practical method for addressing Technical Debt."

---

## Slide 15: Conclusions & Future Directions
- An effective, easy-to-use approach to Technical Debt management.
- Future plans: wider industry validation, automation tools, integration with Agile practices.

**Speaker Notes:**  
"In conclusion, our method effectively manages Technical Debt with clear metrics. Future work includes broader validation, developing automated tools, and deeper integration with Agile workflows."

---

## Slide 16: Q&A and Contact Information
- **Questions?**  
- sabina@bridgein.tech, radu.constantinescu@ie.ase.ro, antonio.clim@csie.ase.ro  

**Speaker Notes:**  
"Thank you for your attention. I look forward to answering your questions and further discussing our approach."

---

## Abbreviation List:
- **TD** – Technical Debt
- **SBD** – Scenario-Based Development
- **Story Cost** – Estimated basic effort for a new feature (Agile story points).
- **TD Cost** – Effort to fix Technical Debt separately from feature development.
- **Story Cost with TD fix** – Effort combining Technical Debt resolution with feature development.
- **Story Cost if TD previously solved** – Reduced effort if Technical Debt was resolved earlier.
- **Interest** – Future additional effort due to delayed Technical Debt resolution.
- **NPS** – Net Promoter Score, measures team/customer satisfaction.
- **CI/CD** – Continuous Integration/Continuous Delivery, automated software integration and deployment practices.
- **Agile** – Flexible, iterative software development approach.
- **KLOC** – Thousand Lines of Code, a measure of software size or complexity.
