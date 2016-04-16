# 2DOF_Helicopter
# There were two different controllers, one for pitch channel while other for the yaw channel.
# Since there were only two controllers, so the system simulated 2D flight. In the first part of the project, a SISO discrete-time controller was designed for the pitch angle. Thus in designing the pitch channel, we ignored the coupling between the two channels and treated the yaw channel as disturbance and vice-versa.
# The design of the pitch controller consisted of two parts.
# The first part involved choosing a reasonable sampling rate and then obtaining the zero-oredr hold discrete equivalent of the plant and designing controller for the pitch channel. The second part obtained the motor voltage (Vp) in response to the step reference input in the pitch channel and calculated the maximum size of the step input that did not result in motor saturation.
# The design of yaw controller in the second section of the project consisted of three parts.
# The first part involved choosing reasonable sampling rate to obtain the zero order hold discrete equivalent of the plant and designing the controller for the yaw channel. In the next section, motor voltage (Vy) was calculated in response to the step reference input in the yaw channel. Finally, the entire system was simulated to investigate the effects of the coupling for the pitch and the yaw channel.
