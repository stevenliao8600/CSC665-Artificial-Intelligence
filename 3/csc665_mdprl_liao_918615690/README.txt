1. Steven Liao, 918615690
2. 
Q1. 
Implement computeQValueFromValues function by finding max qvalue using qvalue equation
Implement computeActionFromValues function by using computeQValueFromValues function to find best action
Implement runValueIteration function by
	initializing values to 0 for all states
	running computeQValueFromValues for all states and their respective actions to get new values
	set values to new values

Q2.
Change noise to 0 so it can cross bridge without falling into chasm

Q3.
a.
Discount to 0.1 so it gets the closest reward and noise to 0 so it won't fall in chasm
b.
Discount to 0.1 so it goes for closest reward and noise to 0.1 so it won't risk falling into chasm
c.
Discount to 0.9 so it goes for largest reward and noise to 0 so it won't fall in chasm
d.
Discount to 0.9 so it goes for largest reward and noise to 0.1 so it won't risk falling into chasm
e.
Discount to 1 so reward are irrelavent to decisions and noise to 0 so it won't go in the wrong direction accidentally and living reward to 1 so it wants to stay alive as long as possible

Q6.
Initialize self.qValues in init function as Counter
Implement getQValues to get values from self.qValues
Implement computeValueFromQValues function by finding max value for all actions
Implement computeActionFromQValues function by finding which action produces the highest value
Implement update function by 
	getting nextQValue from computeValueFromQValues
	use equation to find sample
	update qvalues using equation

Q7.
Implement getAction function by flipping coin to see if we return random action or action from computeActionFromQValues

Q8.
Tried a couple combinations and not worked and tried 'NOT POSSIBLE'

Q9.
It works without me coding anything?

Q10.
Implement getQValue by getting dot product of features and weights
Implement update function by 
	getting nextQValue using similar code from computeValueFromQValues
	getting difference from equation
	updating weight for each feature using equation

3. 30 hrs