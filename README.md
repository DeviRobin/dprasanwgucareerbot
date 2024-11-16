In this task, you will use the Pandorabot environment to create a conversational agent for the given scenario. Your chatbot will interact with students who are about to graduate. You will document the development of the chatbot and investigate the best calibration approaches and AI optimization methods that support the chatbot in having the required functionalities in the most efficient way.

A.  Explain the functionalities of the chatbot and how they will meet the needs described in the scenario.
•	This chatbot has two main functionalities: to identify 5 computing job types and help users choose the job best suited to them via a short quiz. It achieves this using a carousel, cards, and postback buttons.
•	 When opening this chatbot, the user can exchange greetings and tell the chatbot his/her name. The chatbot will remember the name and guide the user to a summary or a ‘help’ option.  The summary involves a carousel with 5 different job cards. Each card can be selected to show more information regarding each career. The help option introduces the user to a short quiz which, when started, will ask the user to choose yes or no to various questions. Depending on the user’s answer, both will suggest a career in card format with the option to see more info regarding the job. The chatbot will achieve its two main functionalities by taking the user through these options.  

B.  Identify five computing job types that your chatbot can recommend based on student interaction with the chatbot.
•	The five computing job types that the chatbot can recommend are: 
o	Database Administrator (DBA)
	This is recommended for users interested in data and who prefer organizing and managing data. 
o	Data Scientist 
	This is recommended to users who are interested in data and prefer analyzing and interpreting data. 
o	Cybersecurity Analyst 
	This is recommended to users who aren’t interested in data and enjoy staying updated with the latest security trends and vulnerabilities. 
o	Software Developer 
	This is recommended to users who aren’t interested in data or security trends but show interest in learning programming languages and frameworks. 
o	Systems Administrator 
	This is recommended to users who aren’t interested in any topics previously addressed and might have a desire to manage and maintain IT infrastructure. 

C.  Provide the generated chatbot code files to support the five identified job types from part B.
•	Please reference attached zip file with code


D.  Explain how the chatbot training cases were selected and how you used artificial intelligence markup language (AIML) to enhance the functionality of the chatbot. Provide examples of the chatbot’s functionality that represent the selected cases at the end of the training process in support of your explanation.
•	Case 1: A student who particularly enjoyed classes where they got to work with data, such as Database Management; however, preferred finding patterns in data rather than managing how data is stored. 
o	In this case,  the user is first asked if they enjoy working with data, with "yes" or "no" buttons. If "yes," a follow-up question appears to determine a preference for data analysis or data management, leading to a relevant career card. Each card has a "more info" button for additional details and an option to return to a carousel of all five possible careers. A mix of postback buttons, cards, and a carousel made via AIML achieves this functionality. 
•	Case 2: A student not interested in data classes or cybersecurity classes but really enjoyed learning programming languages. 
o	In this case, the user is first asked whether they have an interest in data. Upon selecting no, the data science and database career choices are bypassed. The user is then asked about whether they enjoy cybersecurity. By selecting ‘no,’ the cybersecurity analyst career is bypassed. Finally, the user is asked if they enjoy learning programming languages and frameworks, to which they can select ‘yes’. The user is then led to a relevant career card. Each card has a "more info" button for additional details and an option to return to a carousel of all five possible careers. A mix of postback buttons, cards, and a carousel made via AIML achieves this functionality. 

E.  Create an installation manual for the chatbot that includes the web link to access the live chatbot in the Pandorabot platform.
1.	Through a browser, log into pandorabots.com.
2.	Go to https://home.pandorabots.com/dash/bot-directory
3.	In the search bar, type: “drasan” and select the first chatbot
4.	In the chatbot message window, type “hi” or “hello”
5.	Avoid entering one-word answers

F.  Assess the strengths and weaknesses of the chatbot development environment and explain how they supported or impeded the construction of the chatbot.
•	Strengths
o	AIML uses syntax based on XML, making it very intuitive and accessible to new developers. It is very useful in creating predictable interactions with many yes/no answers or simple scripted responses. 
o	The Pandorabot environment allows the deployment of the chatbot on several different platforms, including mobile apps and social media. This allows the chatbot to be easily shared and accessed by others. 
o	The Pandorabot environment has a robust archive of resources to help developers understand AIML and use all of the features of the platform. The use of AIML itself in this environment is helpful, as it is widely used, and there are many resources to gain further information regarding how to create a chatbot. 
•	Weaknesses
o	Though AIML is very intuitive and rule-based, it doesn’t support machine learning. This limits the creator's ability to create a chatbot that can adapt to the user and learn from previous interactions. The chatbot can only be used for simple conversations with predictable responses. 
o	If the requirements for the chatbot grow, for example, if more career options are added, it won't be easy to scale up. Because each pattern and button has to be defined, this can result in a very large script, which becomes hard to manage and correct. 
o	Pandorabot lacks monitoring tools to track specifics of user interactions. Thus, the creator cannot check usage analytics to improve the chatbot in response to how it is being used. 

G.  Explain how the chatbot will be monitored and maintained to improve the final user experience.
•	To improve the final user experience, an escalation path will be put in place to ensure that students who were unable to find an appropriate career path or were dissatisfied with the chatbot’s answer can get assistance. Another important step in maintenance and improvement is to add more career options. Currently, the 5 choices provided only represent a small percentage of careers in the computing field. The questions will also be transitioned from yes/no questions to more multiple-choice questions to offer the user more specific options. Another improvement to the final user experience will include making the chatbot more empathetic to the user’s answers. This empathy can be shown with more questions to ask the user about their feeling about different aspects of their work style or career preference. As more jobs are implemented, a point and tally system can be implemented in place of the current decision tree design. 
•	This chatbot will be monitored by consistently checking chat logs and receiving feedback from students assigned to use it. The chat logs will be regularly checked for errors, and necessary actions will be taken to avoid them. User feedback will be the most important factor in finding ways to improve the chatbot. 
