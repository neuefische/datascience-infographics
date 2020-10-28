<h1 align="center">The EDA Checklist Explained</h1>
<!-- TOC -->

- [_Understanding_](#_understanding_)
- [_Hypothesis_](#_hypothesis_)
- [_Explore_](#_explore_)
- [_Clean_](#_clean_)
- [_Relationships_](#_relationships_)
- [Back to the hypothesis](#back-to-the-hypothesis)
- [_Fine tune_](#_fine-tune_)
- [_Explain_](#_explain_)

<!-- /TOC -->

There is no blueprint fits all on to how to do **Exploratory Data Analysis(EDA)**. A lot of EDA work is like detective work, looking for a suspect, following clues and changing direction based on the clues. Getting good at EDA required though practice. In order to help along we created a small checklist for EDA. This is not an exhaustive list of EDA steps, it is though a minimal checklist.

The infographic is avalible as [pdf](pdfs/EDA_Checklist.pdf) and as [png](images/EDA_Checklist.png). The icons are from [The Noun Project](https://thenounproject.com).


![EDA](images/EDA_Checklist.png?raw=true "EDA Checklist")


## 1.1. _Understanding_ 
What are you trying to achieve? Think of the problem and the data, check the description and get familiarized to the domain. This would be the time you look at the data description, check what columns you have, what types of values.

## 1.2. _Hypothesis_
It is good practice to write down some assumptions and expectations of the data before you start analyzing. These you can then try to confirm or infirm during the EDA.

## 1.3. _Explore_
This is the time to explore the data, check for missing data, extreme values, outliers. Look at the usual suspects when you look at values: the appearance of groups, skewness, appearance of unexpected values, where are the data values centered and how widely are values separated. Do all this meet your expectations from your domain knowledge?

## 1.4. _Clean_
This one is rather clear, deal with extreme values and with missing values. Are the extreme values really outliers? Are the missing values missing for a reason or is it all random? 
Do your variables need to be re-expressed in order to make plots clearer? 

## 1.5. _Relationships_
Are your variables correlated? Are the correlations make sense or could they be caused by confounding factors? 

## 1.6. Back to the hypothesis
Do not forget to check the hypothesis you made at the beginning, you might need to revisit the exploration, clean and relationships phases several times until you find your answers and are confident that they are correct.

## 1.7. _Fine tune_
There are several types of plots that are can make a good analysis be hard to read and to follow: plots that are too small/too large/ missing axes information and descriptions, redundant plots and non-relevant plots. 

Remember that plots should be there to either confirm the expected or to show the unexpected. 
If you are uncomfortable deleting all the work you did, feel free to put it in an auxiliary notebook and maybe you will open it again..

## 1.8. _Explain_
The analysis we usually admire is usually the one that is easy to follow, so why not do the same. Add explanations to your actions, so people reading can follow your thought process, why you did things and how. This can help also in the future or in the present, as you might discover you missed something. 
A good practice is to keep track of this information while you do the analysis, you can even write it all down on paper and at the end put the important things in your analysis in the right place.

----


