On this API, I will be testing this data set to see whether or not the API has a bias towards sex as it pertains to identifying toxicity scores of the text comments. 

My hypothesis is that the API will give lower toxicity scores towards anti-female comments versus anti-male comments. 

H0 = The perspective will deduce anti-male comments as MORE toxic than anti-female comments meaning the toxicity score will be GREATER THAN 0.5 and the anti-male scores will be GREATER THAN THE EQUIVALENT ANTI-FEMALE COMMENT'S TOXICITY SCORE.

H1 = The perspective will dedice anti-male comments as LESS THAN OR EQUALLY toxic than anti-female comments meaning the toxicity square will be EQUAL TO OR LESS THAN 0.5 and the anti-male scores will be LESS THAN OR EQUAL TO THE EQUIVALENT ANTI-FEMALE COMMENT'S TOXICITY SCORE..

First, we define a function to retrieve a comment's toxicity score.

Next, we score random samples from our comment dataset to find a reasonable threshold for toxic comments.

I will iterate over a sample of comments and calculate their toxicity scores using the "toxicity_score" function.

Next we will define comments to categorize whether they are male or female.

Using a sample of 100, I will compute the toxicity scores of male and female comments while also filtering out comments that aren't considered male or female.

I will now find their average toxicity scores to check if there is any significant differences between them.

# Findings
At first, I had anticipated that female hate comments would receive lower toxicity scores than male hate comments, even if there may be a bias in the model to downplay the severity of hate toward women. However, my investigation disproved this assumption, and I was surprised to see that there was no obvious difference.

The outcome of the means for the toxicity ratings for both boys and females was one aspect of my investigation that I found perplexing. I'm not exactly clear what "nan," the outcome, implies. I need to look into this further because it might have an impact on my actual result.

I have a lot of unanswered worries about the potential for bias in machine learning models overall as a result of this effort. Despite the fact that I found no evidence of prejudice in the inquiry I conducted, I am aware that biases can take many various shapes and are frequently not immediately apparent. This gets me thinking about the wider implications of using machine learning to decision-making and how we might ensure that these models are as impartial as feasible.
