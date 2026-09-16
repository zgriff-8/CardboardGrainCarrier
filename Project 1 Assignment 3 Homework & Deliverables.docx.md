# **Assignment 3 \- Homework & Deliverables**

**PROJECT 1 | Team Members:** Ava Owen, Qingyuan Yu, 

*Repository Link:* [https://github.com/zgriff-8/CardboardGrainCarrier/tree/main]

*Coordinate with your team using your new GitHub repository to complete this document before the next class.*

### **Grading Rubric (14 Points Total)**

**Tech Execution (6 Points):**

* **2 pts:** GitHub Repository successfully created, synced, and used by the team.  
* **2 pts:** Whiteboard photo properly embedded using Markdown syntax.  
* **2 pts:** Mermaid.js code successfully generated, properly formatted in a code block, and renders a valid flowchart.

**Mind Map & Concepts (8 Points):**

* **4 pts:** Mind Map Breadth (Photo/Code shows robust brainstorming, integrating the blind stimulus with the 25kg challenge, minimum 15+ nodes).  
* **4 pts:** Concept Evaluations (Each team member completed their pitch thoroughly, directly addressing how geometry manages the load, and accurately completed the constraint checks).

## **Section 1: Tech Setup & AI Digitization (6 Points)**

**1a. GitHub Student Pack (Do this immediately)**

* Register for a free [GitHub Student Developer Pack](https://education.github.com/pack). This gives you free access to GitHub Copilot. *(Approval can take time; do this today).*

**1b. Whiteboard Photo**

[*https://drive.google.com/file/d/10k7dFNnjD0DqJKsb6ANF7Af1fUONnaHo/view?usp=drive\_link*](https://drive.google.com/file/d/10k7dFNnjD0DqJKsb6ANF7Af1fUONnaHo/view?usp=drive_link)

**1c. AI-Generated Mermaid Code**

* **Action:** Open **GitHub Copilot Chat** directly inside VS Code. Click the paperclip icon (or drag-and-drop) to upload the photo of your whiteboard.  
* **Prompt:** *"Act as an expert software engineer. Convert this hand-drawn mind map into valid Mermaid.js flowchart code. Use a top-down (TD) orientation. Ensure the concepts marked with stars are noted."*  
* **Fallback:** If Copilot struggles to read the handwriting, manually construct your map using the visual editor at [MermaidChart.com](https://mermaidchart.com), then click "View Code" to copy it.  
* **Result:** Paste the Mermaid code below and preview it in VSCode using your Markdown/Mermaid extension.

\[flowchart TD
  CGC["CGC: Cardboard Grain Carrier"]

  CGC --> Reinforced["★ Reinforced"]
  CGC --> Protection["★ Protection"]
  CGC --> Intertwined["★ Intertwined"]
  CGC --> Wound["Wound"]
  CGC --> Leverage["Leverage"]

  Reinforced --> StrongMaterial["Strong material"]
  StrongMaterial --> Corrugated["Corrugated cardboard"]
  Reinforced --> NeckYoke["★ Neck yoke"]
  NeckYoke --> ArmStrap["Strap across arm"]
  NeckYoke --> Handle["Handle"]

  Protection --> WeightDistribution["Weight distribution"]
  Protection --> Bag["Bag"]
  Bag --> Slits["Slits"]
  Bag --> Tabs["Tabs"]

  Intertwined --> InterlockingMechanism["Interlocking mechanism"]
  InterlockingMechanism --> PreciseFolds["Precise folds"]
  InterlockingMechanism --> FrictionFit["Friction fit"]

  Wound --> EaseOfCarrying["Ease of carrying"]
  Leverage --> EaseOfCarrying
  WeightDistribution --> EaseOfCarrying

  classDef starred fill:#fff2a8,stroke:#7a5c00,stroke-width:2px;
  class Reinforced,Protection,Intertwined,NeckYoke starred;]

## **Section 2: Rapid Individual Concept Evaluations (8 Points)**

*Each team member claims ONE of the starred concepts from the whiteboard to evaluate against the Phase 0/1 constraints. Ensure your pitches explain the mechanics of the geometric joints.*

### **Concept 1 (Evaluator: Ava)**

* **Concept Name:** Bookbag 
* **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load? *(Use Copilot to refine your phrasing)*  
  * *Answer: The bookbag concept is taking the general idea of a bookbag but modifying it so it will work with cardboard as the material and hold the needed  weight. The general concept is to carry the bag of grain on a person's back so it's more efficient for a person to carry, and the weight will be distributed on the person's back.
* **Constraint Checklist:**  
  * Cardboard ONLY (no glue/tape/metal)? **\[ Y ]**  
  * Operable by BOTH 1 AND 2 people? **\[ Y ]**  
  * What specific fastener-free geometry handles the connection? (e.g., interlocking tabs, friction-fit, precise folds): This concept will likely use a cinch webbing belt concept like a normal bookbag. 
  * What is the biggest risk for failure during the dynamic carry? (creasing, delamination, joint blowout): Biggest risk failure possibilty can be the cinch webbing belt concept coming undone.

### **Concept 2 (Evaluator: Zach Griffith)**

* **Concept Name:** Neck Yoke  
* **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?  
  * *Answer:*  The neck yoke takes the idea of old farm equipment which distributes weight to both sides of the neck and we put the load on one side a padded neck portion a handle on the load and a strap on the other side to balance out the weight.
* **Constraint Checklist:**  
  * Cardboard ONLY (no glue/tape/metal)? **\[ Y ]**  
  * Operable by BOTH 1 AND 2 people? **\[ Y ]**  
  * What specific fastener-free geometry handles the connection?: Likely will use interlocking tabs since it will have multiple parts needing to be put together  
  * What is the biggest risk for failure during the dynamic carry?: The biggest risk is the cardboard bending under the load so we will need to reinforce very well in strategic places

### **Concept 3 (Evaluator: Qingyuan Yu)**

* **Concept Name:** Handle 
* **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?  
  * *Answer:*  
* **Constraint Checklist:**  
  * Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**  
  * Operable by BOTH 1 AND 2 people? **\[ Y / N \]**  
  * What specific fastener-free geometry handles the connection?: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
  * What is the biggest risk for failure during the dynamic carry?: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### **Concept 4 (Evaluator: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_)**

* **Concept Name:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
* **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?  
  * *Answer:*  
* **Constraint Checklist:**  
  * Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**  
  * Operable by BOTH 1 AND 2 people? **\[ Y / N \]**  
  * What specific fastener-free geometry handles the connection?: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
  * What is the biggest risk for failure during the dynamic carry?: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### **Concept 5 (Evaluator: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_) *Only if 5-person team***

* **Concept Name:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
* **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?  
  * *Answer:*  
* **Constraint Checklist:**  
  * Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**  
  * Operable by BOTH 1 AND 2 people? **\[ Y / N \]**  
  * What specific fastener-free geometry handles the connection?: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
  * What is the biggest risk for failure during the dynamic carry?: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*Note: We will use these individual concept evaluations in our upcoming assignment to develop formal design criteria and perform a structured down-selection (using a Morphological Chart or Pugh Matrix). Ensure your GitHub commits are pushed and synced before the next class\!*
