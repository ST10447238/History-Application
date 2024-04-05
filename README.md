# History-Application01
# Image comes here
![image](https://github.com/ST10447238/History-Application/assets/160851446/d2d3146f-ad9b-4992-b321-ab4c43e058b3)
![image](https://github.com/ST10447238/History-Application/assets/160851446/93f1634b-7365-4ba2-b4d5-009665c61a11)

# Purpose of the app
The History application in schools serves several essential purposes in enhancing historical education for students. It provides a complete and engaging platform for learning about various historical events, periods, figuresand a deeper understanding of the past.

Firstly, the application offers a wealth of historical news and articles, keeping students informed on the latest discoveries, archaeological findings, and museum exhibitions. This feature encourages students to analyze current reality and recognize areas for improvement in society.

Secondly, the History application serves as an educational tool for students, offering resources like articles, quizzes, and timelines that supplement traditional history courses. The interactive content caters to different learning styles, helping students better understand historical contexts and develop analytical skills.

# Design considerations
![image](https://github.com/ST10447238/History-Application/assets/160851446/bafc4aa5-335c-408f-b833-26ca070d00a8)

This image above is the first step of the history application, which shows the activity main layout that is important to use when starting an application. Basically, this is a history app / application which is made up of elements from the palette and it also has constrains. It consists of elements such as 2buttons, 2textViews, a plain text and a background image. These elements are important because it will be used by the learners. Each element in this image above has its own role and function in this application, therefore I had to drag and drop the elements from the palette that I needed for the app. I started by dragging and dropping the first text view which I had to rename it as the “History App” which is the heading of the app and what the app is about, I have changed the text size by making it bold to make it easy for the leaners to see what this app is actually about and mainly deals with what. The second element that I have used in the image above is a plain text that I had to rename the id to be enterAge and name it enters age which is the input field where the users or leaners can enter the age of their choices using integers. Then the third element that I have used is the first button which the id is  btnHistory and I named it reveal history, basically the  btnHistory is the button that shows you the displayed history of the age that you have entered ,also this feature is useful for the user to review their activity and can enhance the usability of the application .The fourth element is the second button which the id is btnClear and renamed it  clear this button is used to clear the contents of the text displayed and the age that has been entered by the learner, this feature allows the users or leaners to quickly reset the interface and start  everything  over .The fifth element is the text view which the id is txtDisplay it is responsible tom provide information of the age that has been entered in the plain text also known as enterAge .(IIE,2024)Then the last element is the background which is an art picture of Steve Biko’s face which he is one of the history famous figures.The photograph of Grant Dalton's artwork(Dalton,2023)

![image](https://github.com/ST10447238/History-Application/assets/160851446/a3101481-0018-43d4-a244-db538bc8fff0)

This is the image that shows declaration in the main activity Kotlin code. In this picture above I am declaring four variables which is txtDisplay , btnClear , btnHistory , and enterAge.i have started with a val then the element  which followed by an equal sign then “findViewById” which is a method provided by an Android’s new class and then the  angle brackets “< >"represents the name of the element type that has been used by the specific variable for example enterAgea which is  known a plain text and then there’s (R.id.enterAge) so this is the id of the view being searched for.(IIE,2024) 

![image](https://github.com/ST10447238/History-Application/assets/160851446/d8e299e9-d566-42e4-9ded-ea1dfbb6fb1c)

The third step is to introduce the button history which is responsible to reveal the history information. The history button goes hand in hand with the display because once you press the button it will display the history. In this step I have a var which is the variable name “string”. This variable name it is initialized which is the name of the history famous figure’s name, surname and the date in which the person died and also the place in which the person died in , so in the image above the var outcome is the assigned value of an empty string literal which is indicated by “ “ so that I can enter the required information of that specific history famous figure.(IIE,2024)

![image](https://github.com/ST10447238/History-Application/assets/160851446/4315aae4-c4ad-4aa4-b494-3b39bd604869)

Then in this part it is where I started to use my if statement which for you to see how my code is done. Basically, in this image I am stating the age of the historical famous figure, so I started by say if bracts edit age is == which is the equality operator then the age of the person. Then I used this sign {} in the code, so therefore I have may out come as the information of the famous figure as I have said in my previous picture. (IIE,2024) The people that I have used in this image are one of the people that played a big role in the world and as well their country, they can never be forgotten. The information about these historical famous figures’ names comes from websites, so in this image above the names of the historical figures names that are there, Namely Steve Biko, Cleopatra, George Washington and etc. (OpenAI,2024)

![image](https://github.com/ST10447238/History-Application/assets/160851446/b14a0d9d-2436-4205-98ae-8a854645dfe2)
The txtDisplay is the one that will reveal the information. This is where i introduced my clear button that is reasonable to clear the age that has been entered by the learner  and also it clears all the information that has been displayed , so using the clear button you can enter the first age then clear it and enter the second one without them following each other , same goes as the display because once you clear the age that has been entered then the display also is cleared at the very same time.(OpenAI,2024) 
# utilisation of the github
I used my github app to store my code repoitories.
# conclusion
In summary, the History application in schools is a valuable resource for enhancing historical education. Its engaging content, practical features, and user-friendly design create an immersive learning experience that promotes critical thinking, cultural sensitivity, and a deeper understanding of the past. By using the application, students can develop a well-rounded understanding of historical events and their impact on the present, making them better informed and engaged citizens.

#Refrence
IIE,2024.Introduction to mobile application development.IMAD5112
OpenAi.(2024).ChatGPT(Jan 2022 version).https://openai.com
Dalton,G.(2023).Steve Biko's artwork.www.dalton-arts.com-

#YouTube Video
https://youtu.be/ySH9aX89cMw?si=FvoqMUlYkEIy-s4W
