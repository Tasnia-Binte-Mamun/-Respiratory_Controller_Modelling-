# Respiratory Controller Modelling through Matlab-Simulink

Modeling the chemoreflex regulation of respiration and determining the steady state operation under normoxia and hypoxia condition.

In normoxic conditions, breathing is controlled almost exclusively by the level of CO2 in the arterial blood. However, upon ascent to altitude or during inhalation of a gas mixture containing low O2 content, there is an additional drive to breathe due to hypoxia(PaO2 drops below 70 mmHg).

Since the metabolic consumption rate of O2 and the metabolic elimination rate of CO2 are relatively constant in the steady state, a higher level of ventilation would lead to an increase in PaO2 and a decrease in PaCO2, which in turn would lower ventilation- NEGATIVE FEEDBACK SYSTEM!

<img src="Images\Ventillatory control system.png" alt="Image" width="400" height="200"/>

#### Implemented Simulink model-

<img src="Images\Implemented Simulink model.png" alt="Image" width="600" height="250"/>

#### Observation under normoxic condition-

<img src="Images\Normoxia graph.png" alt="Image" width="600" height="250"/>

#### Observation under hypoxia condition-

<img src="Images\hypoxia graph.png" alt="Image" width="600" height="250"/>

Steady state is achieved under 6L/min which matches with the practical value of ventilation rate under normal condition.

• Steady state under hypoxia is 6.1 L/min which is close to the steady state value achieved under normal condition. This is due to the negative feedback system for decresing PACO2 when ventilation rate increases.

• Initially when ventilation rate is low, PAO2 is low and PACO2 is high. At steady state PAO2 level increased and PACO2 level decreased.
