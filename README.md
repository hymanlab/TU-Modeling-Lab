# Epidemic Modeling Group at Tulane CCS

[![](http://www2.tulane.edu/sse/ccs/images/header_1.png)](http://www2.tulane.edu/sse/ccs/index.cfm)

* [Individual Biographies](PEOPLE.md)
* [*Research Program*](README.md/#research)

## Research
Exploring how to quantify both a mathematical model and the uncertainty, both its and yours.

### You have interest in a phenomenon that exhibits order and chaos
* Physics -- Fluids, Genetics
* Human -- Economics, Social Networks
* Both -- Ecology, Epidemiology

#### You'd like to
* simulate "What If" scenarios
  * explore behavior change, possible mitigations
* at times, short-term prediction -- [http://lega.uazmath.org/?p=389]()
  * approximation; fit a surface to it
* analyze parameter sensitivity (UQ)
  * derivatives; necessarily a wide range?
* helps build our intuition about the whole system -- [http://math.lanl.gov/~mac/papers/bio/HL03.pdf]()

#### So you model it -- describe the order and chaos
* Input Parameters, **x**
* Outputs, **F**(**x**)
  * Deterministic
  * Stochastic
* Known Unknowns (Aleatoric / Accuracy)
  * Measurer not accurate
  * Generally normal distributions?
* Unknown Unknowns (Epistemic / Precision)
  * Missing terms in model
  * Maybe you don't know enough about your phenomenon

#### If you reasonably measure it, you might
* cross-validate your model
  * 10-fold, n-fold, all subsets?
* want parameters such that the model matches measurements
  * minimize residuals, bootstrap


----
