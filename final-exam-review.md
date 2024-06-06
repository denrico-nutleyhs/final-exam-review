
### Physics Final Exam Review Sheet with Practice Problems

  

#### 1. Vector Algebra

  

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

  

#### 2. Kinematics & Projectile Motion

  

**Major Ideas:**

- **Kinematic Equations** (for constant acceleration):

	- $v_f = v_o + at$

	- $\Delta x = v_o t + \frac{1}{2}at^2$

	- $v_{f}^2 = v_{o}^2 + 2a\Delta x$

	- $\Delta x = \frac{1}{2}\left(v_o + v_f\right)t$

- **Projectile Motion**: Motion in two dimensions under gravity. The acceleration in the x-direction is 0.

	- Maximum height, range, and time of flight can be derived using the kinematic equations.
	- In cases where $\Delta y = 0$, the horizontal range is given by $\Delta x = \frac{v_{o}^2 \sin{2\theta}}{g}$
	- In cases where $\Delta y \neq 0$, you'll typically solve a quadratic equation in $t$ using y-components of motion in order to find the horizontal range.

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

  

#### 3. Newton's Laws of Motion

  

**Major Ideas:**

- **First Law (Law of Inertia)**: An object at rest stays at rest, and an object in motion stays in motion with the same speed and direction unless acted upon by an unbalanced force.

- **Second Law**: $\mathbf{\vec{F}_{net}} = m\mathbf{\vec{a}}$. The acceleration of an object is directly proportional to the net force acting on it and inversely proportional to its mass.

- **Third Law**: For every action, there is an equal and opposite reaction. (i.e. If I push on you, you're pushing on me with an equal and opposite force, regardless of our relative strength!)

- **Normal Force**: When considering the contact force between two surfaces, this force is directed perpendicular to those surfaces.

- **Friction**: Frictional force is linearly proportional to the normal force. The constant of proportionality is called the *coefficient of friction*, $\mu$. This coefficient is *dimensionless*.

  

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

  

#### 4. Uniform Circular Motion and Universal Gravitation

  

**Major Ideas:**

- **Uniform Circular Motion**: Motion in a circle with constant speed.

- Centripetal acceleration: $a_c = \frac{v^2}{r}$

- Centripetal force: $F_c = m \frac{v^2}{r}$

- **Universal Gravitation**:

- Newton's Law of Gravitation: $F = G \frac{m_1 m_2}{r^2}$

- $G$ is the gravitational constant ($6.674 \times 10^{-11} \, \text{N}\cdot\text{m}^2/\text{kg}^2$).

- Gravitational force is always attractive and acts along the line joining the centers of two masses.

  

**Practice Problem:**

A 2 kg object is moving in a circle of radius 0.5 m with a speed of 4 m/s. Calculate the centripetal force acting on the object.

  

**Solution:**

1. Centripetal acceleration ($a_c$):

- $a_c = \frac{v^2}{r} = \frac{4^2}{0.5} = 32 \text{ m/s}^2$

  

2. Centripetal force ($F_c$):

- $F_c = m a_c = 2 \times 32 = 64 \text{ N}$

  

---

  

#### 5. Work & Energy Conservation

  

**Major Ideas:**

- **Work**: $W = Fd \cos \theta$, where $F$ is the force, $d$ is the displacement, and $\theta$ is the angle between force and displacement.

- **Kinetic Energy (KE)**: $KE = \frac{1}{2}mv^2$

- **Potential Energy (PE)**:

- Gravitational PE: $PE = mgh$

- Elastic PE (spring): $PE = \frac{1}{2}kx^2$

- **Work-Energy Theorem**: $W

  

= \Delta KE$

- **Conservation of Energy**: Total mechanical energy (KE + PE) is conserved in the absence of non-conservative forces (like friction).

  

**Practice Problem:**

A 10 kg box is lifted vertically 2 m at a constant speed by applying a force of 100 N. Calculate the work done on the box and its potential energy increase.

  

**Solution:**

1. Work done ($W$):

- $W = Fd \cos \theta = 100 \times 2 \times \cos 0° = 200 \text{ J}$

  

2. Potential energy increase ($PE$):

- $PE = mgh = 10 \times 9.8 \times 2 = 196 \text{ J}$

  

---

  

#### 6. Momentum

  

**Major Ideas:**

- **Momentum**: $p = mv$, where $m$ is mass and $v$ is velocity.

- **Impulse**: $J = Ft = \Delta p$

- **Conservation of Momentum**: In a closed system, total momentum before collision equals total momentum after collision.

- $m_1v_1 + m_2v_2 = m_1v_1' + m_2v_2'$

  

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

  

#### 7. Thermodynamics

  

**Major Ideas:**

- **Zeroth Law**: If two systems are each in thermal equilibrium with a third system, they are in thermal equilibrium with each other.

- **First Law (Law of Energy Conservation)**: $\Delta U = Q - W$, where $\Delta U$ is the change in internal energy, $Q$ is heat added to the system, and $W$ is work done by the system.

- **Second Law**: Heat flows spontaneously from a hotter body to a colder one. Entropy of an isolated system never decreases.

- **Third Law**: As temperature approaches absolute zero, the entropy of a system approaches a minimum value.

  

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
