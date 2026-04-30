# EMG and Force Analysis Presentation Notes

---

## 1. EMG–Force Relationship

### Does the EMG envelope generally increase when force increases?
Yes. In the trials analyzed, especially t01, the EMG envelope generally increased as force increased. Linear regression supported this relationship, with positive slopes for both sides:
- Left: 18.0126  
- Right: 23.3907  

### Are there time periods where EMG increases but force does not?
Yes. Possible explanations include:
- Muscle fatigue  
- Co-contraction of antagonistic muscles  
- Changes in muscle length or contraction velocity  
- Differences in neuromuscular efficiency  

### How well does predicted force match actual force?
For trial t01:
- Left Side: Weak relationship (R² = 0.0679)  
- Right Side: Moderate relationship (R² = 0.3320)  

A simple linear model captured only part of the EMG-force relationship.

---

## 2. Coordination Between Arms

### Compare left and right force curves across trials
The left and right force curves generally rose and fell together across trials. In t01, both arms followed similar patterns, although the right arm often produced higher peak forces.

### Are the two arms in phase?
Yes. Both arms were largely in phase, increasing and decreasing force at approximately the same times. No consistent leading or lagging pattern was observed.

### Does coordination change across trials?
Possible changes include:
- Shifts in symmetry  
- Greater reliance on the dominant side  
- Increased variability due to fatigue or motor adaptation  

---

## 3. Trial-to-Trial Differences

### Differences in EMG amplitude patterns
Changes may include:
- Variations in peak amplitude  
- Activation duration  
- Signal smoothness  

Later trials may show increased EMG at similar force levels due to fatigue.

### Differences in force magnitude or variability
- Peak force may decrease in later trials  
- Variability may increase due to fatigue, learning effects, or motivation changes  

### Differences in coordination between arms
Coordination may shift across trials, with one arm compensating for the other if fatigue develops.

---

## 4. Reflection on Using GenAI

### How did GenAI help?
GenAI assisted by:
- Accelerating code generation  
- Explaining functionality  
- Structuring workflow  
- Troubleshooting  
- Simplifying data loading and setup  

### Where did GenAI have limitations?
- Selecting optimal signal-processing parameters  
- Refining smoothing windows  
- Creating highly customized visualizations  

### What did you still need to understand?
A solid understanding of:
- File paths  
- Sampling rates  
- Filtering  
- Downsampling  
- Pandas data structures  

---

## 5. Key Learning Outcomes

### What did you learn about EMG and force?
- EMG is an electrical indicator of muscle activation  
- Its envelope can estimate force, but the relationship is not perfectly linear  
- Signal processing is essential  
- Sampling rates must be aligned  
- Bilateral analysis provides insight into motor coordination  
