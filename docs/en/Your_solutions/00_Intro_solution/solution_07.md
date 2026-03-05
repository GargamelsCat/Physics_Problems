# The Bicycle and the Fly Problem

## Problem Statement
A bicycle is **10 meters** from a wall and moves towards it at a constant speed of **1 m/s**. A fly starts from the bicycle's front wheel and flies towards the wall at **2 m/s**. When it hits the wall, it instantly turns back and flies to the bicycle, and so on. What is the total distance the fly travels before being crushed?



---

## Step-by-Step Solution

While this problem can be approached by summing an infinite series of the fly's individual trips, there is a much simpler "elegant" solution focusing on **time**.

### 1. Calculate the Time to Collision
The fly will stop moving only when the bicycle reaches the wall. Since the bicycle moves at a constant speed, we can find the total time ($t$) it takes to cover the initial distance.

Let:
* $d = 10\text{ m}$ (Initial distance)
* $v_{bicycle} = 1\text{ m/s}$ (Speed of the bicycle)

Using the formula:

$$
t = \frac{d}{v_{bicycle}}
$$

Substituting the values:

$$
t = \frac{10\text{ m}}{1\text{ m/s}} = 10\text{ s}
$$

### 2. Calculate the Total Distance Traveled by the Fly
The fly is in the air for exactly the same amount of time that the bicycle is moving ($10\text{ seconds}$). Because the fly travels at a constant speed, we don't need to worry about the direction changes; we only need its total time and its speed.

Let:
* $v_{fly} = 2\text{ m/s}$ (Speed of the fly)
* $t = 10\text{ s}$ (Total time from Step 1)

The total distance ($D$) is:

$$
D = v_{fly} \times t
$$

Substituting the values:

$$
D = 2\text{ m/s} \times 10\text{ s} = 20\text{ m}
$$

---

## Final Answer
The total distance the fly travels before being crushed is:

$$
20\text{ meters}
$$