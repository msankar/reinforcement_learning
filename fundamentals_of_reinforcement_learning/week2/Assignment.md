## Week2 Assignment

For this assignment you will get experience thinking about Markov Decision Processes (MDPs) and how to think about them. You will devise three example tasks of your own that fit into the MDP framework, identifying for each its states, actions, and rewards. Make the three examples as different from each other as possible.

#### Grading Criteria
You will be graded on each MDP separately. The grading criteria is:

That you have described an MDP and that it is different than your other two.
That you have described the MDP's states.
That you have described the MDP's actions.
That you have described the MDP's rewards.

### Example 1
Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.
An example of an MDP could be a automatic vaccum cleaner which is the agent.
* States here are location in the room, current speed, sensors to detect objects, robot charge whether it is fully charged or not. 
* Actions here are to move forward, backward, left or right and stop. 
* Rewards would be -1 at every time step so that robot is encouraged to vaccum entire room, -50 if it bumps into an object in the room and +1 if it reaches the end of the room.


### Example 2
Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.
An example of an MDP could be determining harvesting of salmon.
* States here are maturity of salmon, breeding season, current population of salmon.
* Action here would be to fish the salmon or not fish.
* Rewards would be -50 at every step as population declines below self sustaining threshold and +1 if population is at a self sustainable level.


### Example 3
Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.

An example of an MDP could be managing queues at DMV.
* States here are length of queue, wait time spent by individuals in queue, service time
* Action here would be to open or close service counters.
* Rewards would be -1 every time step so that agent is encouraged to service quickly and +1 if queue for the counter is cleared up.


