# CodelessAppDev using GPT-3 by team 18

**Codeless Application Development**

Application URL: https://codeless-appdev.herokuapp.com/

API endpoint URL:https://codeless-flask-api.herokuapp.com/

Repo for API generation : https://github.com/suhasAB/Flask_Heroku_API


----------------------

Introduction to the problem statement:
--------------------
In a world where Industry is moving towards Agile model, rapid development and delivery of working software products is a huge challenge.
Codeless Application Development platform intends to reduce the gap between requirements and the deliverable product by using 
Natural Language processing and Deep Learning.

Abstract: 
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
GPT-3's deep learning neural network is a model with over 175 billion machine learning parameters.We have fine tuned GPT-3's Davinci Codex Engine,which is specially designed for Code generation and fine tuned it's parameters to generate code in our Application

Block Diagram:
----------
<img width="731" alt="Screen Shot 2021-12-07 at 9 04 05 PM" src="https://user-images.githubusercontent.com/20688701/145151317-aeb54179-5def-466c-bb96-051a07b6226e.png">



This platform intends to use the excellent text generation capabilities of GPT-3 to generate codes in different programming languages
by passing requirements as prompt to the API call. Once the response is generated, the platform would be able to display the code to a user,
save the particular requirement and response in the user’s Code generation history and will give the user an option to push the code
to repositories such as GitHub. The platform will be able to link and authenticate user’s GitHub profile securely to enable pushing code. 
The code wouold be pushed to a separate github Repository for API generation,which is also deployed on Heroku.
Once the code is pushed to the API generation Repository, API endpoint for the user would be ready to use as soon the latest deployment is completed.
Codeless Application Development platform enables code generation from requirements, renders it to the user to verify 
and provides options to push the code into containerized pipelines to turn it into a deliverable piece of software.

Persona
----------

	-Businesses, Companies, Developers on the lookout for Rapid Development and Deliverables.
	-Non-Techies who want to build things without deep diving into the tech infrastructure.
	-Students who want to understand the flow of Agile Development


Demo:
----------

https://drive.google.com/file/d/1ya-xOxpein5uYZwTQQ4-LMnVFMXIE6-x/view?usp=sharing


Links/References:
----------
OpenAI GPT3: https://openai.com/blog/gpt-3-apps/

Application URL: https://codeless-appdev.herokuapp.com/

API endpoint URL:https://codeless-flask-api.herokuapp.com/

Repo for API generation : https://github.com/suhasAB/Flask_Heroku_API

Flask :https://github-flask.readthedocs.io/en/latest/

Github Oauth: https://github-flask.readthedocs.io/en/latest/

Github Commit from API: :https://docs.github.com/en/rest/reference/repos#create-or-update-file-contents



Deployment on Heroku
----

Heroku:
https://dashboard.heroku.com/apps


-------------------------------------------------------------------------------------------------------------------------------------------------------------------
