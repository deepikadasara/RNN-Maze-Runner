# RNN-Maze-Runner
An undirected graph of 50 nodes contains three entities - the agent, the prey, and the predator. The agent
must catch the prey before the predator catches the agent. These three entities move in the graph until the
game ends. We perform the following tasks at hand :
• Compute U* values, where U*(S) = minimum #rounds taken for the agent to catch the prey, and move
the agent takes decision on the basis of these values
• Build a Model V to predict the value of U* values for all the states and move the agent based on the
predicted values of U*
• Compute U* values for the partial information setting where the exact location of the prey is
unknown, where U_partial*(S) = minimum #rounds taken for the agent to catch the prey, and the agent
takes decisions on the basis of these values.
• Build a Model V to predict the value of U_partial* values for all the states and move the agent based
on the predicted values of U_partial*
