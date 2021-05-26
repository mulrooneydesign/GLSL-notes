# GLSL Functions 

## Common Functions

#### Step
Step returns a value of 1.0 if x > limit or 0.0 if x < limit. 
```glsl
step(limit, x);
```

#### Smoothstep
Like step but take two interpolates between two values. 
```glsl
smoothstep(lowerLimit, upperLimit, x);
```

