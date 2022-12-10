#Major-Project-VERZEO
# Restaurent Reviews 
# Problem statement: Many restaurents want a feedback from their customers so that the management can consider those opinions and work on imporving their restaurent for attracting more people to come and eat at thier restaurent.
During this process of taking the feedback, it becomes very difficult to segregate between the positive and the negative comments. Here comes the picture of machine learning where the machine is trained to identify and segregate these reviews and let the restaurent owner or management know about the positivity and the negativity rate of their restaurent from the peoples perspective.
In this particular project I have tried to build a model which lets us know if the given review is positive or negative where the positive comments are represented by 0 and begative by 1.
The dataset used here is the restaurent reviews dataset which is of file type TSV.This particular dataset containes the Reviews and the output of those reviews weather positive or negative.
Here we have used CountVectorizer in order to eliminate the stop words and make the dataset better for the machine to understand from. On this particular dataset the algorithms which are taken into consideration are only classification models because the result of this model is either true or false, these algorithms are:
1)Multinomaila Naive Bayes and 2)Support Vector Machine.
Joblib is a python standard libarary used here for providing a better way to avoid recomputing the same function repetitively saving a lot of time and computational cost. It is used above pickle because of its capability to save the large numpy arrays faster.
Streamlit changes the datas scripts to a web page and here this us used for the users to type in their reviews. 
The reviews this mentioned is submitted and late rthe result is same in the same page as positive or negative.

Applications of this particular model is that it can be used by many restaurent so that they can give a look at the reviews of the customer and consider it for bringing their business to a higher position in the market.
In addition to this we can also add a statistical analyis by checking out all the reviews and giving out suggestions to the restaurent management about the imporvement required and also let them know what peopel liked the most in their restaurent.
