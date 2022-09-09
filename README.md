# NodeRed-PriorityQueue
One of my Node-Red flows for Google Summer of Code. (Priority Queue pattern implemented...)

DESCRIPTION: 
This subflow splits the messages into 3 categories. First category path has the highest priority, second has the second priority, third has the least... This nodes use is better understood with highly busy flows. Where lots of messages are passing through the flow. Some people might want to send some of these messages before the others by giving them msg.priority variables. By setting these values you make sure that without dealing with the first priority messages the flow doesn't deal with the others.

(FOR A DETAILED DESCRIPTION PLEASE VISIT MY NODE-RED PAGE)
