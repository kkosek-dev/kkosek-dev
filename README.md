# 🏋️‍♂️ Hi, I'm Karson Kosek

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=12&duration=3500&pause=3500&color=D25359&random=false&width=435&lines=Digital+Engineer+(Programmer%2FData+Scientist%2FAvid+Learner))](https://git.io/typing-svg)

🟥 Versatile analyst interested in uniting a plethora of data science tools with refined customer service skills, hungry to augment process value for an organization as well as my own professional development in the business setting. Proven knack for seeing trends in raw data and utilizing statistical findings to better inform holistic decisions. Passionate about staying at the frontier of developing data technologies to better advise operational decisions that directly affect individuals and their lives.

My goal in data science is optimizing accurate insights pulled from data near-automatically, so as to understand data in real time. To me, this represents the epitome of applying computers to the study of human behavior. Thus, I am fascinated by GenAI, in particular LLMs and their production use-cases, from an intelligence point-of-view. It is difficult to trust a transformer model trained on an unfathomably large dataset when we already know that machine learning algorithms, such as the transformer, have never been 100% accurate. Yet, doing this creates a very “intelligent” piece of software, so I have become deeply interested in studying what sets this technological breakthrough apart. 

<h2>Projects</h2>
🟥 All of the following repositories contain the footpath through my interests as I delve deeper into the world of data analytics. Below, I will introduce several projects that I have invested significant effort into in order to broaden my abilities as a data scientist as well as a link to the repository. If for any reason you're interested in further discussing a particular project, feel free to reach out via Github or any of my contact info listed in the sidebar on the left. Thanks for stopping by!
<br></br>

<p align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOXIwZDM3enF3Nzh3cXNudTQ1anFoMnAzeTRnMmltemhydjN5dzltYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/789tnViwHBH0gQ2u7F/giphy.gif" align="center" width="350" height="350" />
</p>

<h3>LLM Prompt Recovery: ML Competition</h3>
> In this project, our objective was to build an inference NLP model that recieved as input an original text and a rewritten version of the orignal and predicts the specific prompt likely given to a different NLP model that would have rewritten the original according to that prompt. In short, build a model that reasons about its own functionality. The sharpened cosine similarity of the T5 text embeddings for the predictions and actual prompts represents the measure of success for this competition, which can be said simply as how "close" our prediction embeddings are to the actual sentence embeddings in the multidimensional vector space. The first part of the build was assembling a carefully balanced blend of text data that we could rewrite with a controlled list of prompts, so we warehoused over 25 open-source text datasets in order to sample from and balance a distribution of different types of text. Once we had the original blend rewritten according to a controlled list of rewrite prompts, we were able to fit this data onto the pretrained, open-model Gemma LLM from Google to align the base weights for words already learned by the model to our niche use-case, in a process called fine-tuning according to low-rank adaptation. In other words, we repositioned the text embeddings of tokens in the existing vector space of Gemma to make the "words"/tokens frequently used in our controlled list of rewrite prompts more likely to selected during inference of the rewritten prompt. Overall, our team "KAD Solutions" placed in the top 40th percetile of participants with a highest-recorded testing simiarity score of 0.62 with the top-scoring team achieving only 0.71 similarity. Limitations presented by the competition itself are discussed further in the repository. 

[Respository](https://github.com/dlerhetal/PromptRecovery/)


<h3>Adversarial Attack Threats in NLP</h3>
> This project explores the development and fortification of NLP architecture at a very basic level, including training a range of classifiers on webscraped product data that increase in complexity, and then attacking the basic NLP model with a highly-advanced AI attacker model to "poison" our NLP model's predictive capacity. I designed the repository to function as an introductory lesson into both NLP and Adversarial AI and hope to publish skeleton copies of the notebooks in the repository for anyone to download and learn from. The first part of the project contains a webscraper that successfully scrapes Walmart's product reviews and assembles them in a MongoDB. Then, the data is prepared to train binary, ternary and categorical NLP sentiment classifiers. The models abilities are demonstrated using a collection of sentences that vary in sentiment classification and point-of-view. After exploring the development of NLP algorithms, one enters the third phase which is conducting an adversarial attack on the binary sentiment classifier using a pretrained adversarial model from the TextAttack Python library design by Jack Morris in 2020. This renders the binary sentiment classifier useless, as anyone utilizing these word transformation attacks could fool the very basic NLP model's predictive capacity. We then introduce a method for giving our basic NLP model more semantic understand of the tokens in order to better protect the NLP model from these word transformation attacks. After implementing the Porter stemming algorithm, we see a dramatic decrease in the effectiveness of the attacker model's word transformation attacks, and more pronounced defence when there is more training data fitted to the NLP model. All in all, this project demonstrates both the effectiveness of adversarial AI in finding weaknesses in machine learning infrastructure and the importance in securing that infrastructure by giving the model as much information as possible as to how it should behave.

[Respository](https://github.com/Hi-Im-Mo/machine-learning-adversarial-attacks)


<h3>US Airline Delay Data Analysis</h3>
> 

#

### 🧰 Languages and Tools

<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
<img align="left" alt="R" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="Pandas" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" />
<img align="left" alt="Jupyter" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" />
<img align="left" alt="AWS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" />
<img align="left" alt="Flask" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" />
<img align="left" alt="PostgreSQL" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />
<img align="left" alt="SQLite" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" />
<img align="left" alt="MongoDB" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" />
<img align="left" alt="VSCode" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<br></br>

