# **Amelia Lei**
### *aclei@ucsd.edu*
### *Section B24 - Mentors: Dr. Ali Arsanjani & Dr. Sam Lau*

## **Quarter 2 Project Brainstorm**
### **1. What is the most interesting topic covered in your domain this quarter?**
The most interesting topic covered in my domain this quarter was the idea of quanitfying misinformation through interpretive predictive modeling. 
Instead of detecting it like a binary classification problem, we were able to break it down into measurable factuality factors like 
frequency heuristic, echo chamber, sensationalism, and credibility. Each of these capture a different dimension of how misinformation spreads.
For example, sensationalism focused on quantifying emotional exaggeration while credibility focused on inferring trustworthiness from
the source. It was also really interesting learning the reason behind why systems that detect misinformation are needed because I did not
know that fact checking has been dismantled by tech giants and the government. 

### **2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
A potential investigation I would like to pursue for my Quarter 2 Project is the extend my current predictive model pipeline into a hybrid
agentic frameowork that incorporates generative ai, retrieval, and collaboration between different agents. My main goal for this 
investigation is to move in the direction of a system that can explain in real time why a statement is misinformation and not just 
whether or not it is misinformation. This investigation would be about building a multi-agent system where we have different agents for
analyzing different factuality agents or we could also have an agent responsible for collecting recent news that needs to be fact checked. 

### **3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
One potential change I'd like to make to my approach is to to scrape more data and aggregate articles from multiple sources. Right now, this project 
is only using data from LiarPLUS which limits the system's ability to generalize to newer or more diverse information. Collecting more data would allow me
to have a more representative and current training corpus and also make it more robust. While the model is important, I would like to take some
more time to expand on the data itself as high quality data will also directly improves model accuracy. By doing this, the system would evolve from 
a static one that's trained on a single dataset to one that's more flexible and can adapt to current events. 

### **4. What other techniques would you be interested in using in your project?**
There are several techniques I would be interested in exmploring in my project. The first one is RAG so that the model focus on retrieving relevant 
information and claims from the articles and be more context aware when scoring. The second technique is function calling in the generative AI portion of
the project where it the LLM can use tools to call the predictive models when doing it's analysis. Lastly, I would also be interested in exploring vector 
databases like ChromaDB also it's something I've never used before. I think this would be really helpful in allowing my model to retain any 
contextual information about past analyses that it's performed. 







