A0153603N e0025709 PER GUNNAR AAKE JAAKONANTTI

What I have done to the environment:

I have changed both of the questionnaires so that relevant questions are asked.

Instructions have been added so the user understands what to do. In the html files (instructions and index).

I added an article with random text called random1.txt It consists of paragraphes made of sentences. The words in these sentences are not real words but random characters made of 0-9, a-z and A-Z. In articles.json I removed most of the links to the articles and kept Article 3 (which for the participants will be known as Article 1), the path to random1.txt was also added here.

The experiment.json file was changed so that only text from random1 and Articla was to be copied. The json file contains 39 different experiments where the 2 first are test cases one for each technique. 3-38 consist of the real cases to be tested. 39 is a break.

In the experiment.html has the third variable been added (also in a way so it saves this variable), my third variable is random vs normal text. A variable called allOrders has been added, this one keeps track of which participant should try which conditon and in which order as well as when the breaks are. Since the tasks are repeated in blocks the variable totalNumberOfTrials is equal to the amount of elements in one array in allOrders. The user is alerted when the testing is over. 

Some smaller changes in some of the documants (to adjust to the changes mentioned above) may have been omitted from this textfile but the things mentioned here are the most important ones and according to the best of my memory the only one I have made.