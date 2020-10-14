# Agent0_ver3
Agent0 is a simulator of  an agent in a square world where there is obstacles, path's costs and where it is possible to define a final target.

In this version, it is possible to add gifts to thw world. 
It also has a new comamnd, "info feelings". Agents return unknown if they feel nothing. Otherwise,
return 'gift', 'zz' or 'dead' if they are in a patch (or cell) with a gift, a 'zz' sound (which means
close to a bomb), or in a bomb patch - agent is dead, but the server doesn't stop, it is up to the agent
to decide if he wants to keep doing things (zoombie, I guess!). 
If the agent is in a patch with a gift, he can actually pick it up (command 'grab').
The server don't keeps information about the number of gifts grabbed. 
It is up to client programmer to decide what kind of benefit or harm it has on the agent.

It is also possible to detect a gift in front of the agent. 
All this new commands only work with the forward, left and right commands.
