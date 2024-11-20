# QUICK PHYSICS SOLVER

## FRICTION
```
Ff = μN                    [friction force]
N = mgcos(θ)              [normal force]
a = μg                    [flat deceleration]
a = g(sinθ ± μcosθ)       [slope acceleration]

STOPPING:
s = v₀²/(2μg)            [distance]
t = v₀/(μg)              [time]
Work = μmgs              [work done]

SOLVE FOR μ:
μ = v₀²/(2gs)           [from stopping distance]
μ = a/g                 [from deceleration]
```

## ENERGY & SPEED
```
NO RESISTANCE:
v = √(2gh)              [drop speed]
v₂ = √(v₁² + 2g(h₁-h₂)) [height → speed]
h = v²/(2g)             [speed → height]

WITH RESISTANCE:
E₁ = mgh                [initial energy]
E₂ = E₁ - Work         [final energy]
v = √(2E₂/m)           [final speed]

PROJECTILE:
h_max = (v₀sinθ)²/(2g)  [max height]
```

## QUICK SOLVES

1. Ski Jump (43m, -10kJ):
```
E₁ = mgh = 31,654J
E₂ = E₁ - 10,000J
v = √(2E₂/m) = 24m/s
```

2. Stopping (v₀, find s):
```
s = v₀²/(2μg)
t = v₀/(μg)
```

3. Slope (θ, find a):
```
a = g(sinθ - μcosθ)
v = √(2as)
```
