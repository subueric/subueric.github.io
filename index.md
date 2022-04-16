##  My ASSIGNMENT!!

The Assignment were given to clearr the basic concepts of Solid Mechanics, Covered during B.tech

### ASSIGNMENT I
#### Q1. Define Solid Mechanics.

The mechanics of deform able solids is more concerned with the internal forces and associated changes in the geometry of the components involved. Of particular importance are the properties of the materials used, the strength of which will determine whether the components fail by breaking in service, and the stiffness of which will determine whether the amount of deformation they suffer is acceptable. Therefore, the subject of mechanics of materials or strength of materials is central to the whole activity of engineering design. Usually the objectives in analysis here will be the determination of the stresses, strains, and deflections produced by loads. Theoretical analyses and experimental results have an equal roles in this field

#### Q2. What is the scope of this branch of Engineering Science?

The Study of Solid Mechanics is essential for several many branch of engineering like, Civil, Mechanical, Aeronautical, Chemical, Agricultural, Textile, etc and applications are found in almost every branch of engineering.
Specifically talking about structural engineering a civil engineer should must know about the material he / she will be using in his/ her domain in order to ensure a safe structure  safe construction environment, not only safety also by studying Solid Mechanics the and observing the strength and etc  of the material available at lesser cost one can reduce the expense the construction. Studying Solid Mechanics will further lead engineers toward discovery and invention of new materials.Studying solid Mechanics will take a generation toward development of sustainable forms of infrastructures and construction techniques.

#### Q3. In what ways does it differ from theory of Elasticity and Strength of Material?

Under strength of material, we deal with a particular problem on an adhoc basis and find particular solution after making many simplifying assumptions. The approach is generally very simple and the emphasis is on finding a practical solution to the particular problem, rather than on understanding the general phenomenon. On the other hand, we try to formulate the problem in most general terms under the theory of elasticity and obtain a general solution, if possible. Obviously, we have to study the problem in greater depth, but the solutions are not easy in most of the cases and a deeper knowledge of mathematics is necessary. Quite often, the problems solved are not of a practical nature and highly idealised loading and boundary conditions are assumed to obtain a solution. This may be a reason why engineers did not take enough interest in it earlier.

#### Q4. What to understand by the term body forces and and Surface forces?

   ![1](https://user-images.githubusercontent.com/40209462/163629108-39a00ca9-e7fe-4be6-9fb4-1833cd8cff0c.jpg)
             
The distinction between surface and body forces is not so easy, sufficient to say that surface forces are acting on an area or surface, whether external or internal, external bond, constant forces(produced by one body pressing against another) or forces produced by thermal expansion or contraction.
The surface fore distribution acts on the surface or area element of the body. The surface force distribution is also known as Surface Traction.
The Body force act on each volume of the body . Examples of this kind of forces are the gravitational force, inertia force and the magnetic force.

#### Q5. Calculate the magnitude of body force and Surface force on the piston 'P'. Assume that the oil pressure is "p", diameter is 'd', its thickness 'h' and its density is rho.

![2](https://user-images.githubusercontent.com/40209462/163629361-cc4b27d5-e250-4e8a-a75f-73d888657c9d.jpg)

_F orce = Pressure x Area_

in case of Surface Force

_Sf = P ∗ 1/4 ∗ π ∗ D^2_

Sf = 1/4 ∗ π ∗ D^2

in case of Body Forces

_Bf = ρ ∗ g ∗ h ∗ 1/4 ∗ π ∗ D^2_

Bf = 1/4 ∗ π ∗ D2 ∗ ρ ∗ g ∗ h


#### Q6. A wooden spherical ball half submerged in water while floating, and roh= 0.5g/cc, explain by neat sketch surface and body forces acting on it.

![3](https://user-images.githubusercontent.com/40209462/163629818-2e6591c2-4deb-47db-9698-ff08857cf919.jpg)

Hence the object will float.
- Here The Gravitational Force is body Force as it acts on each volume(unit) of the ball which is balanced by the surface force.
-Here bouyant Force is the surface force, where it acts as surface force acting in upward direction pushing the ball in upward direction and keeping it floating.
-A small amount of inertia force will be generated, this is also a body force.

#### Q7. Define Statical and Kinematical Indeterminacy?

A structure is statically indetrminate when static equilibrium equations, force and moment equilibrium conditions are insufficient for determining the interval forces and reaction on that structures.

For Example:

![4](https://user-images.githubusercontent.com/40209462/163629953-42c34454-a874-4b83-bba2-571be38d4856.jpg)



So the number of actual reactions are R1, R2,R3 and R4. Where as we just have three equations for plane structures i.e

∑ Fx = 0, ∑ Fy = 0, ∑ Mz = 0

so the degree of indeterminacy= 4-3 = 1, This type of Indeterminacy is know as **statical Indeterminacy.**

**Kinematical Indeterminacy**

A structure is kinematically indeterminate when static equilibrium equation force and moment equilibrium conditions are sufficient for determining the internal forces and reaction on that structures. For Example:

![5](https://user-images.githubusercontent.com/40209462/163630258-617998da-b9a6-4acf-969b-499878785cf0.jpg)

So the unknown reactions are: R1, R2, R3, So now we have three equations of equilibrium i.e 

∑ Fx = 0, ∑ Fy = 0, ∑ Mz = 0
   

so the forces and reactions can be evaluated, such structures are **Kinematically Indeterminate.**


#### Q8. Define Degree of Freedom.

This refers to the maximum number of logically independent values, which are values that have, the freedom to vary, so in context of civil engineering DOF is the lest number of independent displacement removed to define the deformed shapes of a structure. It is the important concept in mechanics, it will be calculated by number of independent unknowns supports - number of available equilibrium equation in the structure .

#### Q9. Define Restraints.

In structural engineering the term restraint is used to denote how a beam is prevented from buckling. To avoid buckling restraints are provided as per the requirements, For Example laterally restrained beams where we provide restraintrs in compression flange to avoid lateral buckling.

#### Q10. Define Releases.

The releases are used as internal hinge in order to bring bending moment to zero,this is very often used in the analysis of statically indeterminate structures by force method, Releasing moment at any point provides extra, equation equal to number of members meeting at that point minus one.

#### Q11. Explain Henderson’s Theory of Statical Indeterminacy.

This theory provides the most comprehensive and fool-proof system for deciding the degree of statical indeterminacy of a complex structure. The structure is
first made determinate by providing enough cuts, so that it resembles a Tree like structure  The degree of in determinacy will be 3 x
No. of cuts, for plane structures and 6 x No. of cuts for space structures. If there are any restraints above the minimum, add them and if there are any
releases, subtract them. If there are N, complete rings in the structure, N cuts are necessary to make it determinate. 

Hence we have,

I=3N+S-R-3, for plane structures

I=6N+S-R-6, for space structures

where,

I = degree of indeterminacy,

N is the number of rings or cuts,

R the No. of releases like hinges, etc. and

S the total No. of restraints at the base or elsewhere.

#### Q12. Using Henderson’s Therory of Statical Indeterminacy Calculate Degree of Freedom of the strctures given in figure.

![6](https://user-images.githubusercontent.com/40209462/163630726-211a9ff4-d104-4b08-8137-16a7de75de9d.jpg)

**For Stucture: a**

I= 3N+S-R-3, for plane structures

N = 1, S = 0, R = 0

= (3 ∗ 1) + (0 − 0) − 3

= 0



**For stucture: b**

I= 3N+S-R-3, for plane structures

N = 1, S = 1, R = 0

= (3 ∗ 1) + (1 − 0) − 3

= 0



**For structure: c**

I=6N+S-R-6, for space structures

N = 3, S = 0, R = 0

= (6 ∗ 3) + (0 − 0) − 6

= 12

   
