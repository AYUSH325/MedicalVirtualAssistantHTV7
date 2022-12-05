# MedicalVirtualAssistantHTV7
Virtual medical assistant. Created for Hack the Valley 7.

Inspiration

In this era, with medicines being readily available for consumption, people take on pills without even consulting with a specialist to find out what diagnosis they have. We have created this project to find out what specific illnesses that a person can be diagnosed with, so that they can seek out the correct treatment, without self-treating themselves with pills which might in turn harm them in the long run.

What it does

This is your personal medical assistant bot which takes in a set of symptoms you are experiencing and returns some illnesses that are most closely matched with that set of symptoms. It is powered by Machine learning which enables it to return more accurate data (tested and verified!) as to what issue the person might have.

How we built it

We used React for building the front-end. We used Python and its vast array of libraries to design the ML model. For building the model, we used scikit-learn. We used pandas for the data processing. To connect the front end with the model, we used Fast API. We used a Random Forest multi-label classification model to give the diagnosis. Since the model takes in a string, we used the Bag-of-Words from Scikit-Learn to convert it to number-related values.

Challenges we ran into

Since none of us had significant ML experience, we had to learn how to create an ML model specifically the multi-label classification model, train it and get it deployed on time. Furthermore, FAST API does not have good documentation, we ran into numerous errors while configuring and interfacing it between our front-end and back-end.

Accomplishments that we're proud of

Creating a Full-Stack Application that would help the public to find a quick diagnosis for the symptoms they experience. Working on the Project as a team and brainstorming ideas for the proof of concept and how to get our app working. We trained the model with use cases which evaluated to 97% accuracy

What we learned

Working with Machine Learning and creating a full-stack App. We also learned how to coordinate with the team to work effectively. Reading documentation and tutorials to get an understanding of how the technologies we used work.

What's next for Medical Chatbot

The first stage for the Medical Chatbot would be to run tests and validate that it works using different datasets. We also plan about adding more features in the front end such as authentication so that different users can register before using the feature. We can get inputs from professionals in healthcare to increase coverage and add more questions to give the correct prediction.
