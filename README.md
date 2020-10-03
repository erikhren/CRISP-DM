# CRISP-DM
These notebooks contain walkthroughs on the important steps in the CRISP-DM cycle.

What is the CRISP-DM cycle?

Also known as "cross-industry standard process" for data mining, CRISP-DM is an open standard process model that describes common approaches used by data mining experts. It is the most widely-used analytics model.

<center>![Image of Yaktocat](https://miro.medium.com/max/1400/1*0YKaiRfOSRQGtjObCQmxIA.png)</center>

**1. Business Understanding**

Focuses on understanding the project objectives and requirements from a business perspective, and then converting this knowledge into a data mining problem definition and a preliminary plan.

**2. Data Understanding**

Starts with an initial data collection and proceeds with activities in order to get familiar with the data, to identify data quality problems, to discover first insights into the data, or to detect interesting subsets to form hypotheses for hidden information.

**3. Data Preparation**

The data preparation phase covers all activities to construct the final dataset from the initial raw data.

**4. Modeling**

Modeling techniques are selected and applied.  Since some techniques like neural nets have specific requirements regarding the form of the data, there can be a loop back here to data prep.

**5. Evaluation**

Once one or more models have been built that appear to have high quality based on whichever loss functions have been selected, these need to be tested to ensure they generalize against unseen data and that all key business issues have been sufficiently considered.  The end result is the selection of the champion model(s).

**6 Deployment**

Generally this will mean deploying a code representation of the model into an operating system to score or categorize new unseen data as it arises and to create a mechanism for the use of that new information in the solution of the original business problem.  Importantly, the code representation must also include all the data prep steps leading up to modeling so that the model will treat new raw data in the same manner as during model development.

*Definitions taken from: https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome*

Be sure to check it out for more in-depth definitions!


