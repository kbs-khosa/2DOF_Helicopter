# 2DOF_Helicopter
# 2 parts of the file show two different controllers, one for pitch channel while other for the yaw channel
# Since there are only two controllers, so the system simulates 2D flight. In the first part of the project, a SISO discrete-time controller is designed for the pitch angle. Thus in designing the pitch channel, we ignore the coupling between the two channel and treat the yaw channel as disturbance and vice-versa.
# The design of the pitch controller consists of two parts.
# The first part includes choosing a reasonable sampling rate and then obtaining the zero-oredr hold discrete equivalent of the plant and designing controller for the pitch channel. The second part obtains the motor voltage (Vp) in response to the step reference input in the pitch channel and calculating the maximum size of the step input that does not result in motor saturation.
# The design of yaw controller in the second section of the project consists of three parts.
# The first part involves choosing  reasonable sampling rate to obtain the zero order hold discrete equivalent of the plant and design the controller for the yaw channel. In the next section, motor voltage (Vy) is calculated in response to the step reference input in the yaw channel. Finally, the entire system is simulated to investigate the effects of the coupling for the pitch and the yaw channel.
