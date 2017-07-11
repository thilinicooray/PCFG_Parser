# PCFG_Parser
CYK Algorithm based parser for a probabilistic context free grammar

* This parser is implemented aiming at PCFG provided in https://github.com/deborausujono/pcfgparser/blob/master/data/weighted.rule
* Download that grammar file from the above repository and place incide data folder with the same file name
* Probabilities of rules are provided in logarithm for the easiness of calculations of joint probabilities and to avoid numerical errors
* Parser is created as a IPython notebook
* Once the notebook is run, insert sentences to get its parse tree.
* An error will be output if any word of the sentence does not belong to the available lexical entries in the grammar
