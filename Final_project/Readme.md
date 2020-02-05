-> The main goal of this final project was to help uncover causal relations in a visa approval/denial dataset of 6 million entries.

-> My part of the project was to use the concepts of Bayesian Networks taught in class to implement a network of the similar kind.

-> Main reasons for choosing the bayseian network was :
				1. Probabilistic Network
				2. Clear estalishment of relations

-> Algorithms for traning the Bayesian Network:
	There exists various methods to train a bayesian network, mainly differing in the way they score the strength of the relations:
			1. Hill Climbing
			2. Structure based learning
			3. Inductive causation

-> After training the model using three different algorithms we took the causal relations that were common to all three.

-> To ensure robustness of the model, this was compared to the Rubin Causal Model done by my teammate and we came to a common conclusion:
		
Conclusion from the experiments:

		-> The main causal relation we were able to uncover was Prevailing wage and the Wage filed.
		-> This was the result across both the models.
		-> There were other causal relations but nothing concrete.
		-> This result also made sense intuitively. 


