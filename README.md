# Health-economic-model
Economic modelling (CEA/BIM/SA) of healthcare interventions
This project is a cost effectiveness model of a pharmacological intervention for endometriosis.
**Rationale for this project :**
  > EndoEcon is a comprehensive health economic model for evaluating pharmacological interventions for endometriosis, utilizing:

  Markov state-transition modeling
  Logistic regression for transition probabilities
  Long-term QALY calculations
  Dynamic costing models
  
**  The model addresses key challenges in endometriosis modeling:
  **
  Heterogeneous and cyclical symptoms
  Delayed and long-term outcomes
  Multi-domain health impacts
  Off-label and hormonal therapies
  
  Lack of female-centric utility values
**project plan:
  EndoEcon/
│
├── data/                   # Data sources and preprocessed datasets
│   ├── utility_values/     # QALY/utility data
│   ├── cost_data/          # Treatment and healthcare costs
│   └── transition_probs/   # Disease progression data
│
├── R/                      # Core model functions
│   ├── markov_model.R      # Markov model implementation
│   ├── regression_models.R # Logistic regression for transitions
│   ├── dynamic_costs.R     # Dynamic cost functions
│   ├── qaly_calculation.R  # Long-term QALY calculations
│   └── validation.R        # Model validation functions
│
├── analysis/               # Analysis scripts
│   ├── base_case.R         # Base case analysis
│   ├── sensitivity.R       # Sensitivity analyses
│   ├── subgroup.R          # Subgroup analyses
│   └── scenario.R          # Scenario analyses
│
├── visualizations/         # Visualization scripts and outputs
References:**
