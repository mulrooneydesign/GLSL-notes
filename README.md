# GLSL Functions 

## Common Functions

#### Clamp
Contrains a value between two limits. Normalize a value between 0.0 and 1.0 for example.
Clamp can take floats or vectors or other types but they must all be of the same type. 
```glsl
clamp(x, min, max);
```

#### Length
Returns the length of a vector
```glsl
length(vector)
```

#### Step
Step returns a value of 1.0 if x > limit or 0.0 if x < limit. 
```glsl
step(limit, x);
```

#### Smoothstep
Like step but interpolates between two values. 
```glsl
smoothstep(lowerLimit, upperLimit, x);
```

