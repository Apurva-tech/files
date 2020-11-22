# Pose-Bot <img src="https://media.giphy.com/media/l3vRaWAPakjiEUQow/giphy.gif" width="80" height = "70" >

### Inspiration ⚡

<strong>In these difficult times, where everyone is forced to work remotely and with the mode of schools and colleges going digital, students are 
spending time on the screen than ever before, it not only affects student but also employees who have to sit for hours in front of the screen. Prolonged exposture to
computer screen and sitting in a bad posture can cause severe health problems like postural dysfunciton and affect one's eyes. Therefore, we present to you : </strong>

<p  align="center"><img height= "300" width = "700" src = "https://github.com/Apurva-tech/files/blob/master/Pose-Bot-title.jpeg"></p>

### What it does 🤖

We created this application to help users maintain a good posture and save from early signs of postural imbalance and protect your vision, this application uses a 
image classifier from teachable machines, which is a <strong>Google API</strong> to detect user's posture and notifies the user to correct their posture or move away 
from the screen when they may not notice it. It notifies the user when he/she is sitting in a bad position or is too close to the screen. 

We first trained the model on the Google API to detect good posture/bad posture and if the user is too close to the screen. Then integrated the model to our application. 
We created a notification service so that the user can use any other site and simultaneously get notified if their posture is bad. We have also included <strong>
EchoAR models to educate </strong> the children about the harms of sitting in a bad position and importance of healthy eyes 👀.

### How We built it 💡

1. The website UI/UX was designed using Figma and then developed using HTML, CSS and JavaScript.Tensorflow.js was used to detect pose and JavaScript API to send notifications.
2. We used the Google Tensorflow.js API to train our model to classify user's pose, proximity to screen and if the user is holding a phone.
3. For training our model we used our own image as the train data and tested it in different settings.
4. This model is then used to classify the users video feed to assess their pose and detect if they are slouching or if they are too close too screen or are sitting in a generally a bad pose.
5. If the user sits in a bad posture for a few seconds then the bot sends a notificaiton to the user to correct their posture or move away from the screen.


### Challenges we ran into 🧠

- Creating a model with good acccuracy in a general setting.
- Reverse engineering the Teachable Machine's Web Plugin snippet to aggregate data and then display notification at certain time interval.
- Integrating the model into our website. 
- Embedding EchoAR models to educate the children about the harms to sitting in a bad position and importance of healthy eyes.
- Deploying the application.

### Accomplishments that we are proud of 😌

We created a completely functional application, which can make a small difference in in our everyday health. We successfully made the applicaition display 
system notifications which can be viewed across system even in different apps. We are proud that we could shape our idea into a functioning application which can be used by 
any user!

### What we learned 🤩

We learned how to integrate Tensorflow.js models into an application. The most exciting part was learning how to train a model on our own data using the Google API. 
We also learned how to create a notification service for a application. And the best of all <strong>playing with EchoAR models</strong> to create a functionality which could 
actually benefit student and help them understand the severity of the cause.  

### What's next for Pose-Bot 📈

#### ➡ Creating a chrome extension

So that the user can use the functionality on their web browser.

#### ➡ Improve the pose detection model. 

The accuracy of the pose detection model can be increased in the future.

#### ➡ Create more classes to help students more concentrate. 

Include more functionality like screen time, and detecting if the user is holding their phone, so we can help users to concentrate. 

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

- [x] HTML
- [x] CSS
- [x] Javascript
  - Tensorflow.js
- [x] Google API
- [x] EchoAR
- [x] Google Poly
- [x] Deployed on Vercel

### Try it out 👇🏽

- 🤖 [Tensorflow.js Model](https://teachablemachine.withgoogle.com/models/f4JB966HD/)
- 🕸 [The Website](https://Pose-Bot.vercel.app/#home)
- 🖥 [The Figma Prototype](https://www.figma.com/file/utEHzshb9zHSB0v3Kp7Rby/Untitled?node-id=0%3A1)

### 3️⃣ Cheers to the team 🥂

- [Apurva Sharma](https://github.com/Apurva-tech)
- [Aniket Singh Rawat](https://github.com/dikwickley)
- [Dev Sharma](https://github.com/cryptus-neoxys)
