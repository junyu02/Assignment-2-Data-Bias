# Assignment-2-Data-Bias
*For privacy, I deleted my API key
 
 This project is to use the Perspective API client to rate the toxicity of each comment and then use python code to analyze the details of the data in the form of tables and charts. Icons are plotted to roughly estimate the threshold of a sub-label as well as to analyze this model for bias and misclassification. 
   
  I think the model fails to recognize Old English (Shakespearean period) (Knave 0.074) as well as when using some uncommon swear words/expletive substitutes (Balderdash! 0.10).

The model it has some malice for some specific groups, for example, at line 41333, I did not think it had any poison, but the model gave it a high score of 0.7976. When I repeatedly looked at the sentence I didn't find any toxicity, only one word: Lesbian Teenager, and when I tested certain words it gave me some wrong scores. I think it's caused by the model being too sensitive, like suck straws. The system gave a high score of 0.84.

The reason for my result I think is very simple, when writing this model, the person writing the code added their own ideas to the code when writing the code, which led to some bias in the code.
