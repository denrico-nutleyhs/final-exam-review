
### Physics Final Exam Review Sheet with Practice Problems

#### 1. Vector Algebra ([Graphical](https://openstax.org/books/college-physics-ap-courses-2e/pages/3-2-vector-addition-and-subtraction-graphical-methods) / [Algebraic](https://openstax.org/books/college-physics-ap-courses-2e/pages/3-3-vector-addition-and-subtraction-analytical-methods) )

**Major Ideas:**

- **Vectors and Scalars**: Vectors have both magnitude and direction (e.g., velocity, force), while scalars have only magnitude (e.g., mass, temperature).

- **Vector Addition**: Use the head-to-tail method or the parallelogram method to add vectors.

- **Vector Components**: A vector can be broken down into components along the x and y axes. For vector $\mathbf{\vec{a}}$ with magnitude $a$ and polar angle $\theta$:

- $a_x = a \cos \theta$

- $a_y = a \sin \theta$

- We can write a vector in *rectangular form* as a sum of its rectangular components: $\mathbf{\vec{a}} = a_x \hat{x} + a_y\hat{y}$
- We can write a vector in *polar form* as a magnitude and direction (polar angle or other expression): *e.g.* "*5 m at 30°*".
- **Resultant Vector**: The vector sum of two or more vectors. Consider the sum of $\mathbf{\vec{a}}$ and $\mathbf{\vec{b}}$. We can calculate the resultant $\mathbf{\vec{r}} = \mathbf{\vec{a}} + \mathbf{\vec{b}}$ by summing components:

- $r_x = a_x + b_x$

- $r_y = a_y + b_y$

- Magnitude: $\left|\mathbf{\vec{r}}\right| = \sqrt{r_x^2 + r_y^2}$

- Direction: $\theta = \tan^{-1}\left(\frac{r_y}{r_x}\right)$
- *Note*: Make sure the angle given by your calculator matches the expected quadrant of your resultant vector. You *may* need to add/subtract 180°!

  

**Practice Problem:**

Two vectors, $\mathbf{A}$ and $\mathbf{B}$, have magnitudes of 5 units and 10 units, respectively. $\mathbf{A}$ is directed at 30° above the positive x-axis, and $\mathbf{B}$ is directed at 45° above the positive x-axis. Find the resultant vector $\mathbf{R}$.

  

**Solution:**

1. Resolve each vector into components:

- $A_x = 5 \cos 30° = 5 \times \frac{\sqrt{3}}{2} = 4.33$

- $A_y = 5 \sin 30° = 5 \times \frac{1}{2} = 2.5$

- $B_x = 10 \cos 45° = 10 \times \frac{\sqrt{2}}{2} = 7.07$

- $B_y = 10 \sin 45° = 10 \times \frac{\sqrt{2}}{2} = 7.07$

  

2. Sum the components:

- $R_x = A_x + B_x = 4.33 + 7.07 = 11.4$

- $R_y = A_y + B_y = 2.5 + 7.07 = 9.57$

  

3. Find the magnitude and direction of $\mathbf{R}$:

- $R = \sqrt{R_x^2 + R_y^2} = \sqrt{11.4^2 + 9.57^2} = \sqrt{130.0 + 91.6} = \sqrt{221.6} = 14.89$

- $\theta_R = \tan^{-1}\left(\frac{R_y}{R_x}\right) = \tan^{-1}\left(\frac{9.57}{11.4}\right) = 40.3°$

  

---

  

#### 2. [Kinematics](https://openstax.org/books/college-physics-ap-courses-2e/pages/2-1-displacement) & [Projectile Motion](https://openstax.org/books/college-physics-ap-courses-2e/pages/3-4-projectile-motion)

  

**Major Ideas:**

- **Kinematic Equations** (for constant acceleration):

	- $v_f = v_o + at$

	- $\Delta x = v_o t + \frac{1}{2}at^2$

	- $v_{f}^2 = v_{o}^2 + 2a\Delta x$

	- $\Delta x = \frac{1}{2}\left(v_o + v_f\right)t$

- **Projectile Motion**: Motion in two dimensions under gravity. The acceleration in the x-direction is 0.

	- Maximum height, range, and time of flight can be derived using the kinematic equations. Remember at maximum height, $v_y = 0$
	- In cases where $\Delta y = 0$, the horizontal range is given by $\Delta x = \frac{v_{o}^2 \sin{2\theta}}{g}$
	- In cases where $\Delta y \neq 0$, you'll typically solve a quadratic equation in $t$ using y-components of motion in order to find the horizontal range.
	- **Enrico's Face Test**: *If you wouldn't put your face there, the velocity isn't zero!* (Guards against students putting $v_f = 0$ when a projectile hits the ground.
	- **Interpreting Motion Graphs**: In addition to reading values off of graphs, (like finding displacement over some time period on a displacement vs. time graph) it's important to be able to read between the lines. The slope of a displacement vs time graph gives us velocity, and the slope of a velocity vs. time graph gives us acceleration. Similarly, the area under the curve of an a vs. t graph gives us the change in velocity while the area under a velocity vs time graph gives us displacement.

**Practice Problem:**

A ball is thrown with an initial velocity of 20 m/s at an angle of 30° above the horizontal. Calculate the maximum height, time of flight, and range of the projectile.

  

**Solution:**

1. Initial velocity components:

- $v_{x0} = 20 \cos 30° = 20 \times \frac{\sqrt{3}}{2} = 17.32 \text{ m/s}$

- $v_{y0} = 20 \sin 30° = 20 \times \frac{1}{2} = 10 \text{ m/s}$

  

2. Time of flight ($t$):

- The time to reach maximum height is $t_{up} = \frac{v_{y0}}{g} = \frac{10}{9.8} = 1.02 \text{ s}$

- Total time of flight $t = 2t_{up} = 2 \times 1.02 = 2.04 \text{ s}$

  

3. Maximum height ($H$):

- $H = v_{y0} t_{up} - \frac{1}{2} g t_{up}^2 = 10 \times 1.02 - \frac{1}{2} \times 9.8 \times (1.02)^2$

- $H = 10.2 - 5.1 = 5.1 \text{ m}$

  

4. Range ($R$):

- $R = v_{x0} \times t = 17.32 \times 2.04 = 35.3 \text{ m}$

  

---

  

#### 3. [Newton's Laws of Motion](https://openstax.org/books/college-physics-2e/pages/4-1-development-of-force-concept)

  

**Major Ideas:**

- **First Law (Law of Inertia)**: An object at rest stays at rest, and an object in motion stays in motion with the same speed and direction unless acted upon by an unbalanced force.

- **Second Law**: $\mathbf{\vec{F}_{net}} = m\mathbf{\vec{a}}$. The acceleration of an object is directly proportional to the net force acting on it and inversely proportional to its mass.

- **Third Law**: For every action, there is an equal and opposite reaction. (i.e. If I push on you, you're pushing on me with an equal and opposite force, regardless of our relative strength!)

- **[Normal Force](https://openstax.org/books/college-physics-2e/pages/4-5-normal-tension-and-other-examples-of-forces)**: When considering the contact force between two surfaces, this force is directed perpendicular to those surfaces.

- **[Friction](https://openstax.org/books/college-physics-2e/pages/4-5-normal-tension-and-other-examples-of-forces)**: Frictional force is linearly proportional to the normal force. The constant of proportionality is called the *coefficient of friction*, $\mu$. This coefficient is *dimensionless*.
- **[Hooke's Law](https://openstax.org/books/college-physics-2e/pages/16-1-hookes-law-stress-and-strain-revisited)**: Hooke's Law describes an ideal spring's response to a displacement from its equilibrium length. As a vector equation, it's stated as: $\mathbf{\vec{F}_{spring}} = -k\mathbf{\vec{x}}$ where $k$ represents the *spring constant*, and $\mathbf{\vec{x}}$ is the displacement from equilibrium. The negative sign indicates that the force provided by the spring is in the *opposite* direction of the displacement. i.e. this is a *restoring* force.
- **Inclined Plane Problems**: In problems involving inclined planes, it's often helpful to work in a coordinate system whose +x axis points up or down the ramp. This usually simplifies our mathematical description of the acceleration, turning our two-dimensional motion problem into a one-dimensional motion problem.
- **Pulley Problems**: Pulleys in this course are *ideal*, i.e. massless and frictionless; they serve only to change the direction of a force. To solve a pulley problem you'll usually draw a free body diagram for each mass, set the tension in their strings to be equal, and solve the resulting system of equations. See [Atwood's Machine](https://en.wikipedia.org/wiki/Atwood_machine#Equation_for_constant_acceleration) for reference.

  

**Practice Problem:**

A 5 kg block is pushed with a force of 20 N across a surface with a coefficient of kinetic friction of 0.3. Calculate the acceleration of the block.

  

**Solution:**

1. Calculate the frictional force ($f_k$):

- Normal force ($N$) = $mg = 5 \times 9.8 = 49 \text{ N}$

- Frictional force $f_k = \mu_k N = 0.3 \times 49 = 14.7 \text{ N}$

  

2. Net force ($F_{\text{net}}$):

- $F_{\text{net}} = 20 - 14.7 = 5.3 \text{ N}$

  

3. Acceleration ($a$):

- $a = \frac{F_{\text{net}}}{m} = \frac{5.3}{5} = 1.06 \text{ m/s}^2$

  

---

  

#### 4. [Uniform Circular Motion and Universal Gravitation](https://openstax.org/books/college-physics-2e/pages/6-introduction-to-uniform-circular-motion-and-gravitation)

  

**Major Ideas:**

- **Uniform Circular Motion**: Motion in a circle with constant speed.

- Centripetal acceleration: $a_c = \frac{v^2}{r}$
- Centripetal acceleration points toward the center of the curve.

- Centripetal force: $F_c = m \frac{v^2}{r}$

- **Universal Gravitation**:

- Newton's Law of Gravitation: $F = G \frac{m_1 m_2}{r^2}$

- $G$ is the gravitational constant ($6.674 \times 10^{-11} \, \text{N}\cdot\text{m}^2/\text{kg}^2$).

- Gravitational force is always attractive and acts along the line joining the centers of two masses.

- **Kepler's Third Law**: We can derive this for the specific case where orbiting bodies travel in uniform circular paths using the equations above, but it also happens to be true of elliptical orbits as well:  $T^{2} \propto r^3$
	- In the case of uniform circular orbits, we find: $T^2 = \frac{4 \pi^2 r^3}{G M}$ where $M$ is the mass of the central body.
  

**Practice Problem:**

A 2 kg object is moving in a circle of radius 0.5 m with a speed of 4 m/s. Calculate the centripetal force acting on the object.

  

**Solution:**

1. Centripetal acceleration ($a_c$):

- $a_c = \frac{v^2}{r} = \frac{4^2}{0.5} = 32 \text{ m/s}^2$

  

2. Centripetal force ($F_c$):

- $F_c = m a_c = 2 \times 32 = 64 \text{ N}$

  

---

  

#### 5. [Work & Energy Conservation](https://openstax.org/books/college-physics-2e/pages/7-introduction-to-work-energy-and-energy-resources)

  

**Major Ideas:**

- **Work**: $W = Fd \cos \theta$, where $F$ is the force, $d$ is the displacement, and $\theta$ is the angle between force and displacement. If there is no component of the force in the direction of motion, *no work is done by that force*. **Work is a scalar quantity**. The SI unit for work is the Joule, J.

- **Kinetic Energy (KE)**: $KE = \frac{1}{2}mv^2$

- **Potential Energy (PE)**:

	- Gravitational PE: $PE = mgh$

	- Elastic PE (spring): $PE = \frac{1}{2}kx^2$

- **Work-Energy Theorem**: $W_{net}= \Delta KE$

- **Conservation of Energy**: Total mechanical energy (KE + PE) is conserved in the absence of non-conservative forces (like friction).
- **Conservative Forces** - Gravity is an example of a conservative force - conservative forces are path-independent and are associated with potential energy functions. For example, if there are two differently-shaped ramps with the same height, gravity does the same work in bringing an object from the top to the bottom. This *does not* mean that both objects will take the same amount of time, however.

  

**Practice Problem:**

A 10 kg box is lifted vertically 2 m at a constant speed by applying a force of 100 N. Calculate the work done on the box and its potential energy increase.

  

**Solution:**

1. Work done ($W$):

- $W = Fd \cos \theta = 100 \times 2 \times \cos 0° = 200 \text{ J}$

  

2. Potential energy increase ($PE$):

- $PE = mgh = 10 \times 9.8 \times 2 = 196 \text{ J}$

  

---

  

#### 6. [Momentum](https://openstax.org/books/college-physics-2e/pages/8-introduction-to-linear-momentum-and-collisions)

  

**Major Ideas:**

- **Momentum**: $\mathbf{\vec{p}} = m\mathbf{\vec{v}}$, where $m$ is mass and $v$ is velocity. Note that momentum is a **vector** quantity. The SI unit for momentum is the kg$\cdot$m/s or alternatively, N$\cdot$s.

- **Impulse**: $\mathbf{\vec{J}} = \mathbf{\vec{F}}\Delta t = \Delta \mathbf{\vec{p}}$

- **Conservation of Momentum**: In the absence of net external force, the total momentum before a collision equals total momentum after a collision. (In the equations below I've used primes to denote final velocities) 

- $m_1v_1 + m_2v_2 = m_1v_1' + m_2v_2'$
- **Characterizing Collisions**: 
	- Elastic Collisions: Kinetic energy is conserved as well as momentum
	- Inelastic Collisions: Momentum is conserved but kinetic energy is not
		- Perfectly Inelastic Collisions: "hit and stick" - represents a maximal loss of kinetic energy.
  

**Practice Problem:**

Two skaters, one with a mass of 50 kg moving at 2 m/s and the other with a mass of 70 kg at rest, collide and stick together. Calculate their final velocity.

  

**Solution:**

1. Initial momentum:

- $p_{\text{initial}} = m_1v_1 + m_2v_2 = 50 \times 2 + 70 \times 0 = 100 \text{ kg}\cdot\text{m/s}$

  

2. Final momentum (conservation of momentum):

- $p_{\text{final}} = (m_1 + m_2)v_{\text{final}} = 120v_{\text{final}}$

  

3. Solve for final velocity:

- $100 = 120v_{\text{final}}$

- $v_{\text{final}} = \frac{100}{120} = 0.83 \text{ m/s}$

  

---

  

#### 7. [Thermodynamics](https://openstax.org/books/college-physics-2e/pages/15-1-the-first-law-of-thermodynamics) & [Entropy](https://openstax.org/books/college-physics-2e/pages/15-6-entropy-and-the-second-law-of-thermodynamics-disorder-and-the-unavailability-of-energy)

  

**Major Ideas:**

- **Zeroth Law**: If two systems are each in thermal equilibrium with a third system, they are in thermal equilibrium with each other.

- **First Law (Law of Energy Conservation)**: $\Delta U = Q - W$, where $\Delta U$ is the change in internal energy, $Q$ is heat added to the system, and $W$ is work done by the system.

- **Second Law**: Heat flows spontaneously from a hotter body to a colder one. Entropy of an isolated system never decreases.

- **Third Law**: As temperature approaches absolute zero, the entropy of a system approaches a minimum value.
- **Absolute Temperature**: **IMPORTANT** - wherever you see a $T$ in a formula, USE KELVIN.
- **Reservoirs**: A thermal reservoir stores heat in such a way that adding or removing heat doesn't change its temperature. For example, if I bring a cup of hot coffee into the classroom, the coffee loses heat to the environment but the temperature of the room doesn't (practically) change. In this case, the classroom is acting as a *thermal reservoir*.
- **Heat Engines**: A heat engine uses differences in temperature to use the flow of heat energy to do physical work. A reversible heat engine produces the maximum possible work for a given temperature difference. The efficiency of such a cycle is called the *Carnot efficiency* and can be calculated as follows: $\eta_{C} = 1 - \frac{T_c}{T_h}$ or equivalently, $\eta_{C} = 1 - \frac{Q_c}{Q_h}$
- **Efficiency**: The thermal efficiency of an engine is the ratio of benefit to cost: $\eta = \frac{W}{Q_h}$ Heat from the hot reservoir is our input, and physical work is our output.
- **Entropy**: We can *loosely* define entropy as a means of quantifying disorder ([Great video here](https://www.youtube.com/watch?v=DxL2HoqLbyA)). There are several ways of expressing this:
	- Clausius Entropy (entropy change for a constant temperature process - measured in J/K): $\Delta S = \frac{Q}{T}$
	- Shannon Entropy (information entropy measured in bits): $H = -\sum p_i \log_2 p_i$

  

**Practice Problem:**

A gas in a piston does 500 J of work while 800 J of heat is added to it. Calculate the change in internal energy of the gas.

  

**Solution:**

1. Using the first law of thermodynamics:

- $\Delta U = Q - W$

- $\Delta U = 800 - 500 = 300 \text{ J}$

  

---

  

#### 8. Coulomb's Law

  

**Major Ideas:**

- **Coulomb's Law**: $F = k \frac{q_1 q_2}{r^2}$

- $F$ is the force between two charges $q_1$ and $q_2$.

- $r$ is the distance between the charges.

- $k$ is Coulomb's constant ($8.99 \times 10^9 \, \text{N}\cdot\text{m}^2/\text{C}^2$).

- **Electric Field (E)**: $E = \frac{F}{q} = k \frac{Q}{r^2}$

- Direction of the field is the direction of the force on a positive test charge.

  

**Practice Problem:**

Two charges, $q_1 = 3 \times 10^{-6} \text{ C}$ and $q_2 = 2 \times 10^{-6} \text{ C}$, are separated by a distance of 0.1 m. Calculate the force between them.

  

**Solution:**

1. Coulomb's law:

- $F = k \frac{q_1 q_2}{r^2}$

- $F = 8.99 \times 10^9 \frac{(3 \times 10^{-6})(2 \times 10^{-6})}{(0.1)^2}$

- $F = 8.99 \times 10^9 \frac{6 \times 10^{-12}}{0.01}$

- $F = 5.394 \text{ N}$

  

---

  

### Tips for Exam Preparation:

- Practice solving problems for each topic.

- Understand the underlying concepts and how different formulas are derived.

- Review class notes and textbooks, and solve practice questions.

- Clarify any doubts with your teacher before the exam.

  

Good luck with your studying!
