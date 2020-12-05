# Merry Cacti <img src="https://github.com/Apurva-tech/files/blob/master/Bot-Avatar.jpg" width="100" height = "100">


### Inspiration ⚡

<strong>Mental health is a stigma in the so called modern society of ours, where people cannot talk about their problems and grievances openly and express themselves. Around 6.7 percent of the U.S. adult population suffer from one or the other mental disease which is often neglected. There are hundreds and thousands of people out there who require attention and need someone to support them. Therefore, we present to you Merry Cacti, your companion which promises comfort and compasion. </strong>

<p  align="center"><img height= "400" width = "600" src = "https://github.com/Apurva-tech/files/blob/master/Landling.gif"></p>

### What it does 🤖

We created this application to help the users suffering from mental health illness and comfort them. Merry Cacti is a <strong>reddit bot</strong> which finds the user's post which implies depressive and self destructive sentiments and replies happy thoughts and redirects them to our website where we provide a platform to help such users express themselves anonymously and help each other using a subreddit. 

We at first extracted the data to train our model by using the reddit json file and then process the data to create a final csv file. We used nltk and spacy to pre-process the Reddit post text data and analyse if the text is suicidal or depressive, and comment on the post accordingly. We created a website where people can view our bot replies on Reddit and chat with our bot integrated into the website. 

### How We built it 💡

1. The website UI/UX was designed using Figma. 
2. We used Python to create the bot. We extracted the data from a subreddit json file and processed the required data to create the final file.  
3. For training our model we used scikit-learn TFDVectorizer which gave the best model accuracy of 95%, to create predictions if the post depicts suicdal or depressed behaviour.


### Challenges we ran into 🧠

- Extracting the data for training the model.
- Pre-processing the model 
- Creating a chat-bot for the website and integrating it.
- Using reddit API json file to create embeds of the replies and posts for the website.

### Accomplishments that we are proud of 😌

We created a fully functional bot which can emphathize with human being and comfort them. We are very proud to share that some comments did help our users and made them feel better themselves. We integrated a chatbot to our website which can help users to talk and make them feel loved and supported. 

### What we learned 🤩

We learned basic structure of natural language processing using nltk and spaCy using Python. And creating and integrating a chatbot in our website. 

### What's next for Merry Cacti 📈

#### ➡ Creating a functional forum

So that the user can communicate anonymously and help each other. 

#### ➡ Improve the NLP model. 

The accuracy of the NLP model can be increased in the future.

#### ➡ Improving the functionality of our chat-bot

Include more functionality like increasing the accuracy of the bot-replies. 

### Help File 💻

- [x] Clone the repository to your local directory
- `git clone https://github.com/cryptus-neoxys/posture.git`

- [x] `npm i -g live-server`
- Install live server to run it locally

- [x] `live-server .`
- Go to project directory and launch the website using live-server

- [x] Voilla the site is up and running on your PC.

- [x] Ctrl + C to stop the live-server!!

### Built With ⚙

#### The Website

- [x] HTML
- [x] CSS

#### The Reddit Bot
- [x] Python
  - NLTK
  - Numpy
  - Pandas
  - Seaborn
  - SpaCy
  - Scikit-learn
  - PRAW


### Try it out 👇🏽

- 🤖 [Tensorflow.js Model](https://teachablemachine.withgoogle.com/models/f4JB966HD/)
- 🕸 [The Website](https://Pose-Bot.vercel.app/#home)
- 🖥 [The Figma Prototype](https://www.figma.com/file/utEHzshb9zHSB0v3Kp7Rby/Untitled?node-id=0%3A1)

### Cheers to the team 🥂

- [Apurva Sharma](https://github.com/Apurva-tech)
- [Aniket Singh Rawat](https://github.com/dikwickley)
- [Dev Sharma](https://github.com/cryptus-neoxys)
- [Vinayak gupta](https://github.com/gvinayakgupta)
