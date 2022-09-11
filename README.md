# Static_UR5_Data
**Collaborative Robot Static Anti-Gravity Data



During the real industrial robot movement, robot joint angles, joint angular velocities, and joint motor currents are recorded via ROS-Melodic software which handles the communication (@~125Hz). Static data is then extracted by finding the sample points at which the robots angular velocities are equal to zero. Data is then formatted in Comma Separated Values (CSV) formatted data. This data can be exploited in machine learning approaches for static modelling of the industrial robot behavior. This data may be utilized research investigating static industrial robot model including its gravity terms and static friction terms.

Data is composed of 

1. joint angle data: Positions_reduced.csv
2. joint angular velocities: Velocities_reduced.csv
3. joint motor currents: Efforts_reduced.csv

