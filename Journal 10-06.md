# Finite Element Analysis  10/06/2025
## FEA Purpose
 - To determine if the initial frame design has any unforseen flaws in regard to points of excess stress, strain or deformation within the expected usage bounds.
## FEA Findings
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/fea1.png)
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/fea5.png)
 - It was found that the initial design had points where the stress had reached 30mPa in some edge conditions of the expected usage case, 30mPa is approaching/at the limit of PLA so those points need to be further optimised.
 - The high stress points were often near sharp edges on the frame as seen below
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/fea2.png)
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/fea3.png)
## FEA Redesign
 - The frame was redesigned to minimise high stress points and to improve strength. Sharp points on the model that caused spikes in stress were rounded or developed to include more material
 - Further FEA may be used to remove unnessecary material and for topological optimisation.
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/fea6.png)

# Computational Flow Dynamics 10/06/2025
 - A flow simulations uncovered a vortex that can be generated. The simulation was run at approximately 20m/s and at a pitch of 30* forward.
 - The vortex would not have any huge disadvantages besided minor drag and slight negative lift generation, if deemed nessecary at a later date, cannards/diffusers can be added to fix this.
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/cfd.png)

# Camera Angle 10/06/2025
 - The camera angle is a decision that needs to be made. There are infinite options for the camera angle.
 - ## Pros/Cons of different angles:
 - ### High angle (0*\>x>30* upward):
 - **Pros:** Make it possible to see forwards at aggressive pitch angles, good for high speed/acceleration and race drones.
 - **Cons:** Difficult to see horizon when stationary/slower, limited/no view of ground.
 - ### Mid angle (-10*\>x>0*):
 - **Pros:** Provide balanced view up and down good for flying with awareness at moderate speed while maintaining the ground and horizon.
 - **Cons:** Not very good at high speed, or while stationary.
 - ### Low angle (-45*\>x>-10*):
 - **Pros:** Very good view while stationary or at low speed, very user friendly.
 - **Cons:** Low awareness at high speeds, only able to look down from drone (you're in the sky; there's not much to see above you)
 - ### Birds eye view (-90*\>x>-45*):
 - **Pros:** Good view for ground surveilance and while stationary.
 - **Cons:** Absolutely no awareness when moving forward.
 - ## Possible solutions:
 - 1. Fixed angle; pick an angle that is optimal for use case and design frame to only allow camera to be mounted on that angle.
   2. Different mounting; design frame with different mounting locations that allows the camera to be remounted at different angles (easy design, hard to change angle)
   3. Moving mount; design frame to have moving parts to allow for quick selection between 2-5 pre-determined angles (hard to design, easy to change)
   4. Electronic control; design mounting and frame for servo motor to be mounted to control angle of camera between fixed limits (IMPOSSIBLE to design, SOO SOO cool)

