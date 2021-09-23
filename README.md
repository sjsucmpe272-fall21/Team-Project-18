# Team-Project-18 -> Project Ideas

**Project Idea 1.**


**Codeless Application Development**
----------------------

Introduction to the problem statement:
--------------------
In a world where Industry is moving towards Agile model, rapid development and delivery of working software products is a huge challenge.
Codeless Application Development platform intends to reduce the gap between requirements and the deliverable product by using 
Natural Language processing and Deep Learning.

Abstract (Rough draft): 
----------------------------
Codeless Application Development platform takes in user requirements in Well-formed English Language sentences 
and can generate the code for required functionality in required programming languages such as Python, JavaScript, Java and SQL etc. 
This platform then also provides an option to push that function/code generated by NLP onto a repository, 
which is linked to a containerized CI/CD pipeline that can create/update an application instance on the cloud that’s deliverable instantly.
The user has an option to either push the code or just verify that the code generated by the platform is in sync 
with their requirements which were input to the system. The platform also can support tasks such as 
generating English text which explains the given input program/function code.

Approach
----------
The platform uses OpenAI’s GPT-3 API under the hood to take in Requirements in simple English sentences and to generate logical and accurate code. 
Generative Pre-trained Transformer 3 (GPT-3) is an autoregressive language model that uses deep learning to produce human-like text. 
GPT-3's deep learning neural network is a model with over 175 billion machine learning parameters.

This platform intends to use the excellent text generation capabilities of GPT-3 to generate codes in different programming languages
by passing requirements as prompt to the API call. Once the response is generated, the platform would be able to display the code to a user,
save the particular requirement and response in the user’s Code generation history and will give the user an option to push the code
to repositories such as GitHub. The platform will be able to link and authenticate user’s GitHub profile securely to enable pushing code. 
We can either choose to write our own build files for CI/CD pipelines or try to generate them from the platform’s code generator.
Codeless Application Development platform enables code generation from requirements, renders it to the user to verify 
and provides options to push the code into containerized pipelines to turn it into a deliverable piece of software.

Persona
----------
-Businesses, Companies, Developers on the lookout for Rapid Development and Deliverables.
-Non-Techies who want to build things without deep diving into the tech infrastructure.
-Students who want to understand the flow of Agile Development

Links/References:
----------
[OpenAI GPT3] : https://openai.com/blog/gpt-3-apps/

Serverless computing options to package and deliver the generated code:

[IBM] : https://developer.ibm.com/depmodels/serverless/

[AWS] :  https://aws.amazon.com/lambda/

[RedHat] : https://cloud.redhat.com/learn/topics/serverless


-------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Project Idea 2.**
**JARVIS - A personal assistant portal**

Introduction to the problem statement:
-----------------------------------------
With all the multiple things one is involved in daily - Academics, Personal technical growth, Job prep, blogging, meetings, socializing, fitness, self-improvement etc, we plan to create a single portal (a web application) wherein users can keep track of their progress across each dimension.

Abstract (Rough draft): 
----------------------------
Logging Component: 
    - This will be the one base component that will be available throughout.
	- This component will accept a text or image input at a certain point in time. And once the user saves the data, it will be persisted in a database (mostly MongoDB) under appropriate title.
	- Why image input?
		- Because at times, we usually take notes physically with pen and paper. Once done, user can have it clicked and just upload it on the portal

Progess Component:
	- This will be the one base component that will be available for each Module.
	- It will be present alongwith each component and it will render the number of hours spent day wise.
		eg. Sept 1 - 2 hrs
			Sept 2 - 0 hrs
			Sept 3 - 0 hrs
			Sept 4 - 0 hrs
			Sept 5 - 0 hrs
			Sept 6 - 0 hrs
			Sept 7 - 0 hrs
			Sept 8 - 4 hrs
			Sept 9 - 0 hrs
			Sept 10 - 1 hrs
			Sept 11 - 0 hrs
			Sept 12 - 0 hrs
			Sept 13 - 0 hrs
			Sept 14 - 2 hrs
			Sept 15 - 0 hrs
			Sept 16 - 0 hrs
			Sept 17 - 3 hrs
			Sept 18 - 0 hrs
			Sept 19 - 0 hrs
			Sept 20 - 0 hrs
			Sept 21 - 0 hrs
			Sept 22 - 5 hrs
			Sept 23 - 0 hrs
			Sept 24 - 6 hrs
			Sept 25 - 0 hrs
			Sept 27 - 0 hrs
			Sept 28 - 0 hrs
			Sept 29 - 1 hrs
			Sept 30 - 0 hrs

		We can then give metrics like:
			- users longest continuous streak
			- plot a graph of users hours spent

MODULES:
	1. Academics
		- (Lecture notes etc.)
		- (I feel this would be very useful if later, say after a year or two, I quickly remember that some professor had mentioned something in his lecture and I want to refer to that...)
		- To ensure that a student gives equal amount of time to all his courses.

	2. Personal technical growth
		- Personal projects, 
		- Technologies to learn (it usually happens you learn something of some tech, but then since you didn't log it, you dont recollect the progess you had done earlier; leading you to start all over or worst - drop the learning all together)
		- Certifications, exams prep

	3. Job Prep
		- Internship search
		- Leetcode

	3. Blogging
		- Say you solved a technical problem after hours of googling and you want to record it step-by-step. 

	4. Meetings
		- To store all the MoMs (Minutes of Meeting)

	5. Personal Space
		- Entertainment
			- Collate all your music playlists (links or youtube video embeds) at one place like youtube music, spotify, Amazon Music etc.
		- Motivation / quotes etc.
			- you can have your own articles, or you can make some notes over some motivational video that you saw on youtube.

Approach
----------
- The application will be a MERN application. 
- Since ReactJS is used for frontend, we may use React-Native to build an app for it

Persona
----------
- Students
-------------------------------------------------------------------------------------------------------------------------------------------------------------------


**Project Idea 3.**
--------------------
