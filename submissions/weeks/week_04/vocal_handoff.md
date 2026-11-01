```
HANDOFF
turns: 23
learns by: example-in-context (simple, picture-first)

domain: point processes | level: 2 | milestone: 2 reached | anchor: marginal intensity
marginal intensity | claim: no | prior: none | end: unused | no quote
other deployed: emission function, intensity surface
other open: intensity, observation window, softplus floor, equator boundary, thinning, closed form for c

domain: statistical inference | level: 2 | milestone: 2 reached | anchor: metric gaming
ablation | claim: no | prior: none | end: deployed | "Ablation sudy can help find how the model performs if one variable is controlled."
leaderboard | claim: no | prior: none | end: introduced | no quote
generalization | claim: no | prior: none | end: deployed | "the model becomes complex and overfit the data so generalization becomes worse."
overfitting | claim: no | prior: none | end: deployed | "As the parameter are added, the model becomes complex and overfit the data"
metric gaming | claim: no | prior: none | end: unused | no quote
model selection | claim: no | prior: none | end: introduced | no quote
other deployed: standard error of the paired differences, latent variable, gauge freedom, partial pooling, leave-one-cycle-out cross-validation, held-out log-likelihood, quadrature mesh
other open: tie, candidate, parsimony, nested, identifiable, flat direction, gauge choice

domain: solar cycle physics | level: 2 | milestone: 2 reached | anchor: wing
hemispheric asymmetry | claim: no | prior: none | end: deployed | "because the studies found assymentry in the hemispheres!"
other deployed: buoyancy threshold, drift track, belt width
other open: wing (misused, corrected), butterfly diagram, time profile, gate, fade width, latitude profile, amplitude, flux tube, Zeeman effect, hemicycle
```

## My knob (Task 36)

```python
MY_KNOB = dict(
    stage    = "gate",
    values   = ["equator_fade"],
    default  = "none",
    question = "Does something beyond the buoyancy threshold suppress sunspots as the belt nears the equator?",
    expected = "No improvement: the threshold already empties the low latitudes, so w_fade only fits noise (overfitting).",
)
```

Menu row for Task 38 (from the session): `spec_of(pooling="hemi")` — "Do the north and south wings have a different time-profile shape?" Expected: improve (hemispheric asymmetry).
