__Description__

- [Donors Choose](DonorsChoose.org) receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.
- DonorsChoose.org expects to receive close to 500,000 project proposals.

__Problems they need to solve__

- How to scale current manual processes and resources to screen 500,000 projects so that they can be posted as quickly and as efficiently as possible
- How to increase the consistency of project vetting across different volunteers to improve the experience for teachers.
- How to focus volunteer time on the applications that need the most assistance.

__Problem Statement of this project__

- The goal of the project is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved or not, using the text of project descriptions as well as additional metadata about the project, teacher, and school.
- DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.

__Deployment__
- Deployed using Flask.
- [Reference Video](https://youtu.be/VkYGkfa6VGs)

__Model Architecture__
- Used word embeddings for the __text feature__ along with LSTM and pre-trained Glove model.
- Tokenized the __categorical features__ and passed them separately.
- Concatenated all the features and passed them as an input to the feed forward newral network
 ![First](https://github.com/shashank3009/donors-c/blob/main/Model%20Architectures/model1.png)

