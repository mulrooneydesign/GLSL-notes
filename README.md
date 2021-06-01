# GLSL Functions 

## Common Functions

#### Abs
Returns the absolute value of a parameter. Returns 1 for -1. Absolute values are the same value but not negative.
```glsl
abs(x, min, max);
```

#### Clamp
Contrains a value between two limits. Normalize a value between 0.0 and 1.0 for example.
Clamp can take floats or vectors or other types but they must all be of the same type. 
```glsl
clamp(x, min, max);
```

#### Dot Product
dot returns the dot product of two vectors, a and b. i.e., ax × bx + ay × by.
Returns a scalar.
```glsl
dot(a, b);
```
When two vectors are at right angles to each other the dot product is zero.

#### Length
Returns the length of a vector
```glsl
length(vector);
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

#### Mix
mix — linearly interpolate between two values
```glsl
mix(colorA, colorB, strength);
```

## General GLSL Notes
"fragCoord", "fragment coordinate" is an input variable telling us at which pixel we are on the screen. The coordinate center is the left bottom corner. (0,0)
