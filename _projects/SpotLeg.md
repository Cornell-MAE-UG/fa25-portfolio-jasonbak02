The Boston Dynamics robot dog, Spot, is an excellent example of how system dynamics is shaping the future of engineering. As an autonomous being, correction and response torques are absolutely essential in every action to ensure that Spot can maintain its balance when put in a tough situation. This video shows how Spot instantaneously responds to different disturbances, including forces acting on and against it. 

https://youtu.be/aFuA50H9uek?si=QoWX1XclWWRxhHMK

Taking this a step further, I decided to try an implement a simple PD controller using MATLAB, modeling the joints of the legs as connected vectors, similar to a 2D pendulum. This helped me learn a lot about controller responses, including the meaning of Kp and Kd gains, and how we can adjust them to our advantage when designing complex machines. 

To see the Matlab file: [Report]({{ '/assets/Matlab3260.pdf' | relative_url }})

To see my group’s work: [Report]({{ '/assets/MAE3260FinalReportRobotDog.pdf' | relative_url }})