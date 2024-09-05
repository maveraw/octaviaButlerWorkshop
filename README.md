# Session3: Octavia Butler Predicts the future

[https://lu.ma/cin107ny](https://lu.ma/cin107ny)

In this women and nonbinary workshop we'll be working with open-source AI to stage a small debate between Octavia Butler and other figures based on her famous essay "A Few Rules for Predicting the Future" that she wrote for Essence in 2000.

​No worries if you missed the past 2 workshops! We meet you as you are, and you can start wherever you want and go at your own pace.

* [https://sudoroom.github.io/octaviaButlerAIConversationAgentNight/](https://sudoroom.github.io/octaviaButlerAIConversationAgentNight/)

## AI For Conflict Resolution and Meetings

While we initially mostly as a group had the "ick" for AI in conflict resolution, it's being used in surprisingly helpful ways around the world, often to make discussions more inclusive!

- [Al Jazeera - Can AI Mediate Conflict better than Humans?](https://www.aljazeera.com/news/2024/2/29/can-ai-mediate-conflict-better-than-humans)

> "For generations, power brokers would gather behind doors to make decisions affecting people far and wide. Digital technologies can now allow the process to be relatively more inclusive.

# Session2: Octavia Butler Open Source AI Meetup RAG and Vector Databases 

* https://lu.ma/m3qsibqb

We Continue our Open-Source AI workshop from last week with a focus on Vector Databases and RAG with inspiration from Octavia Butler, science fiction goddess.

​We will focus of course on open-sourced models and also see if it’s not too hard to get an open-sourced generative AI model on a raspberry pi for hardware hacking projects.

![image](session_01/images/Butler-Perret_BACK-ofbook-1.jpg)

## Pre-requisites 

### Step 1: Clone the Repository

- Open your terminal and Run:
  
  ```
  git clone https://github.com/sudoroom/octaviaButlerWorkshop.git
  ``` 
If you encounter issues with Git, visit [GitHub's Git Guide](https://docs.github.com/en/get-started/using-git).

### Step 2: Set Up Python 3 Environment

- Install Python 3: Download and install from [python.org](https://www.python.org/downloads/).
  
- Create a Virtual Environment:
    - Navigate to your project directory.
    - To create a virtual environment, Run:
       ```
        python3 -m venv .venv
       ```
  
### Step 3: Activate the Virtual Environment:
- On Linux/MacOS:
  ```
  source .venv/bin/activate
  ```
- On Windows:
    - Activate the script from powershell, as it is ususally disabled/restricted.
    - Run as administrator: 
       ```
       Set-ExecutionPolicy -ExecutionPolicy Unrestricted
       ```
     - Navigate to the ternminal and activate by running:
       ```
       .venv\Scripts\activate
       ```
If you face issues, check out the Python Virtual Environments Guide.

### Step 4: Install Dependencies

- Make sure you’re in your virtual environment.
- Run to upgrade pip:
  ```
  pip install --upgrade pip
  ```
- Install required packages:
  ```
  pip install -r requirements.txt
  ```
  If you have dependency issues, refer to Python Dependency Management.


### Step 5: Install Ollama

We're using open-source models with the Ollama open-source framework. Now that we've set up our python environment locally, we are ready to go.

- Download [Ollama](https://www.ollama.com)
- Run 
  ```
   ollama
  ```
  (depends on which computer you have, open the ollama app on a mac and run a command on debian linux, will update)
- List the models you have downloaded to your computer
  ```
  ollama list
  ```
If you encounter runtime errors, check the [Python Error Handling guide](https://docs.python.org/3/tutorial/errors.html).

## Additional Resources

- We've now set-up a local environment along with a python environment.
- To set-up a virtual environment all along: Visit [anaconda.org](https://anaconda.org/).
- If you get stuck at any point, use the [Python Documentation](https://docs.python.org/3/) or reach out to the GitHub Issues section of the repository for community help.
  
  
> Hooray!!! You've just completed the workshop. Give yourself a pat on the back.

## About this meetup

The purpose of this [Octavia Butler Open-Source AI meetup](https://sudoroom.org/inspiration-from-goat-octavia-butler/) is to get our hands dirty with code and face-to-face interaction at the SudoRoom hackerspace in Oakland. AI is coming our way for all its good or bad qualities, but we should be proactive and try to figure out way to deal with it humanely.


* From the first session [https://sudoroom.org/inspiration-from-goat-octavia-butler/](https://sudoroom.org/inspiration-from-goat-octavia-butler/)
