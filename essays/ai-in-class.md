---
layout: essay
type: essay
title: "AI in Class"
# All dates must be YYYY-MM-DD format!
date: 2024-05-04
published: true
labels:
  - AI
  - Education
  - Software Engineering
---

<img width="300px" class="rounded float-start pe-4" src="../img/ai/sv-ai.jpg">

### I. Introduction
The emergence of AI in education is revolutionizing the way we learn and teach. One of the most advanced areas is Large Language Models, which are now accessible to everyone and transforming the educational landscape. The rapid improvement in the quality and speed of AI tools makes them increasingly useful in education. For instance, the ability to ask questions and receive answers in natural language is a game-changer. In Software Engineering, AI tools can significantly assist in coding by generating code based on prompts, debugging by identifying and correcting errors, and suggesting alternative solutions. In ICS 314, we explored various AI technologies, including GitHub Copilot as an extension of IntelliJ, and ChatGPT for answering questions and conducting experiments to analyze responses. Additionally, I utilized Bard, Gemini, Claude.ai, and locally installed models as writing aids for essays.
```
NAME                    	ID          	SIZE  	MODIFIED
gemma:7b                	430ed3535049	5.2 GB	2 months ago
llama2:70b              	e7f6c06ffef4	38 GB 	2 months ago
llama2:latest           	78e26419b446	3.8 GB	3 months ago
llama2-uncensored:latest	44040b922233	3.8 GB	2 months ago
llama3:70b              	bcfb190ca3a7	39 GB 	13 days ago
llama3:latest           	71a106a91016	4.7 GB	2 weeks ago
mistral:latest          	61e88e884507	4.1 GB	2 months ago
```
### II. Personal Experience with AI:
As part of the course, we installed GitHub Copilot in IntelliJ IDEA.
I have used AI in class this semester in the following areas:

1. Experience WODs e.g. E18
   Almost all of the Experience WODs I tried to finish without using an AI. I found a helpful GitHub Copilot for "E27: Five problems 2". The task was about combining two lists by alternating taking elements. I asked GitHub Copilot to write a function that combines two lists. The result was not exactly what was needed, but I wrote more detailed instructions and got a workable code.
2. In-class Practice WODs
   Github Copilot was intact on all my WODs, but I used it as autocomplete only most of the time.
3. In-class WODs
   In class "WOD: Javascript 2" I used Bard for the whole task. I got the workable solution in seconds by copying and pasting the assignment code completely. About this special case, I will write more in the next section. Another example is "WOD: Coding Standards" I used Google Bard to write a function that checks how many words 'love' in the text. At that time I was learning functional programming in JavaScript and I wanted to see how Bard would write a function that uses functional programming. It worked well and I got a decent solution on time.
4. Essays
   I tried different techniques in the essay writing process. In an essay "High Hopes" that was completely generated I felt like cheating. The essay itself is really good, but I would not consider it as mine, however writing a prompt (the experiment part) is mine, but it stays behind the essay. Most of the time I wrote the outline and did some research for each paragraph, then I asked LLM to improve each paragraph. It gave a good result overall. I also tried to write the whole essay and asked LLM to improve it, that gave me the better feeling that I was not cheating on the content because most of the text was mine and just paraphrased with better structure, vocabulary, and grammar.
5. Final project
   Besides Github Copilot I tried not to use any AI for the final project. I wanted to learn and understand the concepts by myself. But I faced with a problem that I could not solve for some time. I worked on the avatar picture upload feature and I couldn't find the proper way to store pictures on the server. I asked Github Copilot chat and it gave me a good and easy solution. I used it and it worked well.
   Example:
```
me: I am trying to store the profile image in the database as encoded text, how can I do that?
copilot: To store the profile image as encoded text in the database, you can use the FileReader API to read the image file as a Base64 string. Here's how you can modify the ImageProcessor component in Profile.jsx to achieve this: 
...
const reader = new FileReader();
      reader.onload = function(e) {
         onChange?.onChange(e.target.result);
      }
      reader.readAsDataURL(files[0]);
...
```
I think I could find the solution by myself, but it would take more time and effort. I think it was a good decision to ask AI for help in this case.
6. Learning a concept / tutorial
   I used AI to pull out some concept information like "How object in JavaScript different from an object in Java?" and received a detailed response. The exciting part is that I can ask about details on each part of the response. I asked "What is a prototype in JavaScript?" and got a detailed explanation of the prototype chain and how it works in JavaScript. I think it is a good way to learn new concepts and get detailed information about them.
7. Answering a question in class or in Discord
   As part of in-class training, we used ChatGPT to answer questions and analyze. The teacher gave us a prompt that would be answered by ChatGPT with correct and wrong answers, so we learned that we couldn't trust it 100%.
8. Asking or answering a smart-question
   I found LLM very helpful in writing smart questions. I asked LLM is my question was looking smart, and it gave me good feedback, so I was able to correct the question before I posted it online.
9. Coding example e.g. “give an example of using Underscore .pluck”
   Github Copilot was a blast to handle such questions because it has access to the code that I am working on and it gives contextualized answers.
10. Explaining code
    I didn't try to use AI for this purpose yet, because I could explain the code by myself. I think it is a good way to learn and understand the code.
11. Writing code
    The autocomplete feature of GitHub Copilot was very helpful in writing code. I could write the code faster and with fewer errors. I think it is a good way to write code. It also has the feature of scrolling through alternative solutions, so I could learn different ways of solving the same problem.
12. Documenting code
    I haven't tried this yet, but I think it would be helpful to write comments and documentation for the code. At least mark the code where comments would be useful. I will try it in the future.
13. Quality assurance
    I believe AI can improve the code the same way it does in writing an essay. I will try to use it in the future to improve the quality of the code.
14. Other uses in ICS 314 not listed above
    I used AI-generated background [music](https://suno.com) while studying at home for the class. It made me feel better and more focused.

### III. Impact on Learning and Understanding:
Using AI in my learning experience has significantly influenced my comprehension, skill development, and problem-solving abilities. The incorporation of AI technologies has enhanced my understanding of software engineering concepts by providing real-time assistance and feedback. For instance, GitHub Copilot has helped me generate code snippets, identify errors, and suggest alternative solutions, thereby improving my coding proficiency. Additionally, AI tools like Bard, Gemini, and Claude.ai have facilitated the writing process by offering suggestions for structuring essays, improving grammar, and enhancing vocabulary. By leveraging AI technologies, I have been able to learn new concepts, explore different coding techniques, and enhance my problem-solving skills. The interactive nature of AI tools has made learning more engaging and effective, enabling me to grasp complex topics more easily. On the other hand, I think that using AI in the learning process can make students lazy and less creative. It is important to use AI as a tool to improve the learning process, not as a replacement for it. For example, I used AI for In-class "WOD: Javascript 2" which was about drag racing judgment calculation. I copy pasted the task to LLM and got the solution in seconds. I didn't learn anything from that task. Not about drag racing, not about JavaScript. I felt like I was a mailman who delivered the message without reading it.
I think it is important to use AI in the right way to improve the learning process, not to replace it.

### IV. Practical Applications:
Besides class, I used LLM for troubleshooting hardware issues for faulty scientific devices. I asked the question:
```
me: I am repairing a scientific tool that has force sensor reading acting up. I replaced the capacitors, but it didn't help. What else can I do? 
llm: A repair challenge!

Sorry to hear that replacing the capacitors didn't resolve the issue with force sensor readings. Let's troubleshoot further to identify the potential cause and possible solutions.

Before we dive in, please note that I'll provide general guidance, as I'm not familiar with the specific design or schematic of your device. If you have access to the manual, datasheet, or technical support resources, it may
be helpful to consult them as well.

**Potential causes:**

1. **Faulty force sensor**: The sensor itself might be damaged or faulty, causing erratic readings.
2. **Analog-to-digital converter (ADC) issues**: The ADC converts the analog signal from the force sensor to a digital signal. Problems with the ADC could lead to incorrect readings.
3. **Signal conditioning circuitry**: The signal conditioning circuitry, including amplifiers, filters, and voltage regulators, might be malfunctioning or introducing noise.
4. **Power supply issues**: A faulty power supply or voltage regulator could cause instability in the force sensor readings.
5. **Electromagnetic interference (EMI)**: EMI from nearby devices or wiring could be affecting the force sensor's performance.

**Troubleshooting steps:**

1. **Visual inspection**: Carefully inspect the force sensor, ADC, and surrounding circuitry for signs of damage, corrosion, or overheating.
2. **Check power supply**: Verify that the power supply voltage is stable and within the recommended range.
3. **Signal probing**: Use an oscilloscope to probe the analog signal from the force sensor and the digital signal after the ADC conversion. This can help identify if the issue is in the analog or digital domain.
4. **Sensor calibration**: Check if the force sensor needs recalibration or if the calibration process was not properly performed.
5. **Swap components**: If possible, swap out the force sensor or other suspect components with known good ones to isolate the faulty part.
6. **Consult documentation and resources**: Review the device's manual, datasheet, and technical support resources for troubleshooting guides specific to your model.

**Additional suggestions:**

* Clean the PCB and connectors to ensure good electrical connections.
* Verify that the firmware or software is up-to-date and functioning correctly.
* If you have access to a similar working unit, compare the two devices to identify any differences in their behavior or circuitry.

By systematically following these steps, you should be able to identify and potentially resolve the issue with your force sensor readings. Good luck!
```
The response was very helpful and I was able to find that faulty sensor was a problem. At the same time, I learned about potential problems that could cause the issue and how to troubleshoot them. I think it is a good way to use AI in real-life problems. It shows you more ways to solve the problem and you can choose the best one for you. It speeds up the process of troubleshooting and gives you more confidence in your decisions.

### V. Challenges and Opportunities:
While AI technologies have enhanced my learning experience in software engineering, there are certain challenges and limitations that I have encountered. One of the main challenges is the potential over-reliance on AI tools, which can hinder critical thinking and creativity. I am risking to become a mailman of solutions, not a problem solver. It is important to strike a balance between utilizing AI for assistance and developing independent problem-solving skills. Additionally, the accuracy and reliability of AI-generated content can vary, leading to potential errors or misconceptions. It is essential to critically evaluate the suggestions provided by AI tools and verify them through additional research or analysis. Despite these challenges, there are numerous opportunities for further integration of AI in software engineering education.
One of the opportunities is the personalization of learning experiences through AI adaptive learning platforms. By analyzing students' performance, preferences, and learning styles, AI tools can tailor educational content to meet individual needs and enhance engagement.

### VI. Comparative Analysis:
In software engineering education, traditional teaching methods, which rely on lectures, textbooks, assignments, WODs, and quizzes compared to AI-enhanced learning experiences, have their own advantages and limitations. Traditional teaching methods provide a structured and systematic approach to learning, enabling students to acquire foundational knowledge and skills. However, they may lack interactivity, personalization, and real-time feedback, which are essential for engaging students and promoting active learning. On the other hand, AI-enhanced learning experiences offer personalized, interactive, and adaptive learning opportunities that can significantly enhance students' comprehension, problem-solving abilities, and creativity. By leveraging AI tools, students can receive instant feedback, access a wealth of resources, and engage in collaborative learning activities. While traditional teaching methods are effective in delivering content and assessing students' knowledge, AI-enhanced learning experiences have the potential to revolutionize software engineering education by providing personalized, engaging, and effective learning experiences. By combining the strengths of both approaches, educators can create a dynamic and innovative learning environment that fosters creativity, critical thinking, and lifelong learning.

### VII. Future Considerations:
AI is emerging rapidly, and its integration into software engineering education is expected to grow in the future. In case software engineering will survive as a profession and not be completely replaced by AI or AGI, education enhancements will play a significant role in the future. AI technologies such as GitHub Copilot, Gemini, and ChatGPT will continue to evolve and improve, offering new features, capabilities, and applications for students and educators. Professors will have to find a way to teach students how to use AI in the right way, so they can improve their learning process, not replace it. Additionally, AI tools will become more sophisticated and intelligent, enabling students to engage in complex problem-solving tasks, collaborative projects, and interactive learning experiences. The future role of AI in software engineering education will likely focus on enhancing personalized learning experiences, promoting creativity and innovation, and fostering lifelong learning skills. Educators will need to adapt their teaching methods, curricula, and assessments to incorporate AI technologies effectively and optimize students' learning outcomes.

### VIII. Conclusion:
The advent of Artificial Intelligence (AI) has transformed software engineering education by providing a suite of powerful tools that enhance the learning experience. Large language models, code generation, and intelligent assistants facilitate natural language interaction and real-time assistance, revolutionizing the way students learn. AI-powered tools like GitHub Copilot, Gemini, and Claude have been extensively utilized for code generation, debugging, essay writing, concept learning, and problem-solving. These tools have proven invaluable in generating code snippets, identifying errors, suggesting alternative solutions, and refining writing quality.
However, there is a risk of over-reliance on AI tools, which can stifle critical thinking and creativity. While AI has augmented comprehension, skill development, problem-solving abilities, engagement, and understanding of complex topics through real-time feedback and interactive experiences, excessive use can promote laziness and discourage creative thinking. A balanced approach is essential to harness the benefits of AI while nurturing independent problem-solving skills. Practical applications, such as troubleshooting hardware issues, demonstrate AI's value in providing guidance and accelerating processes.Nevertheless, challenges like accuracy concerns and potential over-reliance must be addressed. Opportunities abound for developing personalized adaptive learning platforms and enhancing interactive collaborative experiences. A hybrid approach that combines traditional structured teaching methods with AI-enhanced personalized and interactive experiences can create an innovative environment that fosters creativity, critical thinking, and lifelong learning skills. To optimize responsible and balanced AI use, guidelines, best practices, curriculum integration, continuous updates, and educator training are recommended. By adopting a thoughtful and informed approach, educators can harness the potential of AI to enhance software engineering education while nurturing independent problem-solving abilities.


Written by Dmitry Gordeev. Enhanced by Llama3 LLM.
