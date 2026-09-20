This repository contains the reproducible implementation of the numerical simulations presented in the paper “Proposal of a Pricing Model for UTM Service Providers.”

The study proposes a provider-level pricing framework for Unmanned Aircraft System Traffic Management (UTM) services. The model links the tariff charged for a service request to observable operational cost drivers, including reservation time, reserved airspace area, peak-hour use, and procedural complexity.

The Brazilian BR-UTM environment is used as the institutional application context.

Repository contents

The main notebook is:

BR_UTM_Pricing_Simulations_Colab.ipynb

It is compatible with Google Colab and reproduces the deterministic numerical experiments described in the paper.

The notebook includes:

implementation of the proposed tariff equation;

reproduction of the worked numerical example;

synthetic operational scenarios;

adverse-weather scenarios;

sensitivity analysis of operational variables;

standardized one-at-a-time sensitivity analysis of model parameters;

tornado-chart visualization;

sensitivity analysis of the provider remuneration margin; and

export of the simulation results to CSV files.
