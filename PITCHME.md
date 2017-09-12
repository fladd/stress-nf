# STRESNET WP5

## Neurofeedback training based on global network shifts to increase stress resiliance

+++

### WP5.1

**Establish reliablity of neurofeedback signal by demonstrating that individuals can:**
  1. gain general control over this measure
  2. receive significantly more information from this than from a verbal instruction
  3. use this information to counteract an externally induced brain response
  4. after training, apply this learned mechanism in the absence of feedback

+++

### WP5.2

**Hypothesis**:

Neurofeedback training based global network shifts lowers stress reactivity in a laboratory test outside of the scanner

+++

### WP5.3

**Hypothesis**:

Post-neurofeedback training benefits generalize to real-world outcomes in terms of increasing stress resilience

---

## What neurofeedback signal?

+++

### My initial intuition
**Develop sophisticated connectivity measure:**
  - identify representative areas for each of the three core networks
  - compute some measure that captures their activation relative to each other (e.g. between-network cohesion; Young et al. 2017)

+++

### Erno's original plan
**Develop algorithm  sensitive  to  individual  “fingerprints”  of  neural  responses  to  stressors:**
  - train classifier on individual patterns of neural activity elicited in response to brief stressor, known to trigger rapid shift towards salience network
  - use resulting set of weights to combine activity patterns measured in real-time (in response to the same challenge) into a single score expressing the similarity of the current brain state to the training state

---

### CAN-relevant rtfMRI-NF studies

+++?image=assets/CAN_NF_Studies.png&size=contain

Note:
Study | Subjects | Context | NF target | NF type
----- | -------- | ------- | --------- | -------
Johnston et al. (2010) | healthy | emotion imagery | subject dependent region | activation
Hamilton et al. (2011) | healthy | emotion imagery | sACC | activation
Zotev et al. (2011) | healhty | positive AB memories | Amygdala | activation
Veit et al. (2012) | healthy | threat-related stimuli | AIC | activation
Linden et al. (2012) | MDD | emotion imagery | subject dependent region | activation
Zhang et al. (2013) | healthy| working memory | dlPFC | activation
Ruiz et al. (2013) | schizophrenia | emotion recognition | AIC | activation
Scheinost et al. (2013) | subclinical anxiety | contamination anxiety | OFC | activation
Young et al. (2014) | MDD | positive AB memories | Amygdala | activation
Yuan et al. (2014) | MDD | positive AB memories | Amygdala | activation
Sitaram et al. (2014) | criminal psyhopaths | emotion imagery | AIC | activation
Moll et al. (2014) | healthy | affiliative emotion imagery | whole brain (SVM) | state
Groene et al. (2014) | healthy | perception of emotions | ACC | activation
Zotev et al. (2014) | healthy | emotion regulation | Amygdala | activation
Sarkheil et al. (2015) | healthy | aversive stimuli | LPFC | activation
Zilverstand et al. (2015) | females with spider phobia | anxiety provoking stimuli | dlPFC/Insula | activation
Zang et al. (2015) | healthy | working memory | dlPFC | activation
Gerin et al. (2016) | PTSD | personalized trauma scripts | Amygdala | activation
Li et al. (2016) | healthy | positive AB memories | subject dependent map (SVM-RFE) | state
Hamilton et al. (2016) | MDD | aversive stimuli | subject dependent SN nodes | activation
Paret et al. (2016) | BPD | aversive stimuli | Amygdala | activation
Cohen Kadosh et al. (2016) | healthy | emotion imagery | Insula | activation
Sherwood et al. (2016) | healthy | working memory | dlPFC | activation
Young et al. (2017) | MDD | positive AB memories | Amygdala | activation
Li et al. (2017) | healthy | positive/negative AB memories | subject dependent map (SVM-RFE) | state
Nicholson et al. (2017) | PTSD | personalized trauma words | Amygdala | activation
Koush et al. (2017) | healthy | positive social stimuli |dmPFC/Amygdala (DCM) | (effective) connectivity
