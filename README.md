# Ai_training_explain

there are 2 type of Ai_engineer in my opioion :

I. The trainer

these type of dev was do everything on there own only thing that not there own is a LLMs or an Ai model becuzz create one from scratch it hard
need alot of people to collab and cost alot of money .

the process that i have learn from these type of dev is :

they first create a data structure and a requirements .txt so there know what they need than they write a env for 
an api key so they can use a model depend on what there use (cost money like 0.10$ per model for an api of course)
they that start trian everything they like for good perpose use ipynb instead of py because ipynb is a hold like
libary for python user it = juypter and google collab (recomend) than they start to get a data (if some advance dev they writte a another model to find a data on the web that they want automaticly wwithout uplaod any data)
of course if u new like me wehat we do it write a dataset or uplaod dataset so we can train it . they r 3 type of 
get the dataset to trian in my opioion :

1.write ur own dataset and train it
2.uplaod a dataset from ur device
3.automaticly search for dataset on the internet and train it (if UR pc cost 1M$ ofc)

----------- that all i know here will continue once i learn more ------------------------


II. The sit down and use alr exit tool

+ the tikoker : 

these type of dev (not a dev exactly) they use an exit tool llike n8n too create they own ai agent 
cuz it ezz no code experince need just connect a damn wire together than boom ur have ur own ai agent
i know it easy and ofc if ur want a freelancer just learn it and figure it out how to use it in what
suaition that can make money it cost abit too cuz nth free in this world;


+ The Bot spammer

type of mf who use openclaw intergret with another application like telegram or dc or whatever u decide
u just need to set up a openclaw correctly tthan intergret it with ur telegram bot by using bot_father (goated btw i use that alot)
ofc it not end here if u expert on u can use openclaw to connect intergret with alot of application at the same time
and work together perfectly like for example use it to serarch on the internet than store it in notion tthan 
give an infor throu telegram and u can set it up for any other perpose depend on what ur want this type of shit
only work and have money is Freelandcer it goat for find money on internet but cant become an ai- engineer cuzz it too ez no

---- still more but learn --






#note

dont include a dataset that u train together with the python code folder put it on different folder







#create r own ai agent
I. create a virtua enviroment
the requirements.tstx files

what is a virtual enviroment ?
virtual enviroment is a isolateed place where we can instal these indepencies and then we can work in the enviromen for the Project.

# to open ur env

PS D:\Data\AI_Agent> python -m venv venv
PS D:\Data\AI_Agent> .\venv\scripts\activate 
# install the requirment
on the requiremens.txt
if  put something like this 
langchain
wikipedia
langchain-openai
langchain-community
langchain-anthropic
python-dotenv
pydantic
u have to install all the packet 
by write out likr this 
(venv) PS D:\Data\AI_Agent> pip install -r .\requirements.txt

but if it nott work :
try this :
pip install langchain wikipedia langchain-openai langchain-community langchain-anthropic python-dotenv pydantic

# after all the instal we import our model my cxreate new file ,py

than we import:
from dotenv import load_dotenv
from pydantic import BaseModel
from langchain import ChatOpenAI
from langchain_anthropic import ChatAnthropic


load_dotenv()


llm = ChatOpenAI(model=gpy-4o-mini") we import ouur model from OpenAi and the model was gpt-44o-mini

llm2 = ChatAnthropic=("claude-3-5-sonnet-20241022")

we import our model from clauudde model etc etc

#note : even ur use universer u still need an api key 
so go to.env

