# vocal_handoff — ButterflAI 2.0, Week 02 (`02_rate_1d.ipynb`)

```
HANDOFF
turns: 32
learns by: example-in-context, with plots and worked numbers on real data

domain: point processes | level: 2 | milestone: 2 reached | anchor: inhomogeneous Poisson process
inhomogeneous Poisson process | claim: no | prior: none | end: introduced | "no quote"
intensity function | claim: no | prior: none | end: deployed | "lambda(s) is an intensity function, it id th enumber of events per year per hemispheric"
compensator | claim: no | prior: none | end: introduced | "no quote"
thinning | claim: no | prior: none | end: introduced | "no quote"
time-rescaling theorem | claim: no | prior: none | end: introduced | "no quote"
other deployed: none
other open: event, Exp(1)

domain: statistical inference | level: 2 | milestone: 2 reached | anchor: quadrature
log-likelihood | claim: no | prior: none | end: deployed | "here logL is the sim of. log of al the event rates."
maximum likelihood estimate | claim: no | prior: none | end: deployed | "the expected count of 1400 for 19N mean is not fitted to MLE"
quadrature | claim: no | prior: none | end: introduced | "no quote"
unconstrained parameterization | claim: no | prior: none | end: introduced | "no quote"
QQ plot | claim: no | prior: none | end: unused | "no quote"
Kolmogorov–Smirnov statistic | claim: no | prior: none | end: unused | "no quote"
identifiability | claim: no | prior: none | end: unused | "no quote"
profile likelihood | claim: no | prior: none | end: unused | "no quote"
other deployed: none
other open: likelihood, constrain, skewness, refinement

domain: solar cycle physics | level: 1 | milestone: 2 not yet | anchor: onset
emergence rate | claim: no | prior: none | end: introduced | "no quote"
onset | claim: no | prior: none | end: misused | "Onset is the time where the event is first seen."
other deployed: hemispheric cycle
other open: emergence, differential rotation
```

## Notes for next session

- **Prediction on record (Section 5, before running Task 14):** the student predicted that the onset s₀
  will be recovered worst, "because there is empty space between −6 and −4". Revisit against the Task 14
  recovery table and in Section 7.
- **Not yet covered:** Section 5 directive points 1 (mechanism when the integral term is dropped), 4
  (verifying an implementation vs testing a model); all of Section 6 points 2–4 (constant-rate QQ
  prediction, tie policy, what a passing KS test does not establish); all of Section 7.
- **Open misconception:** onset (fitted switch-on time) vs first event (data) vs s = 0 (15° crossing).
