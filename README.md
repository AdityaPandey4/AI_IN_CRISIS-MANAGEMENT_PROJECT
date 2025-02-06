This was my project in which I attempted to provide a solution (or) an additional help to the Disaster Management team using Artificial Intelligence and new advancements in Large Language models

# ABSTRACT 

In times of national crisis, such as natural disasters or pandemics, efficient resource allocation and strategic decision-making are critical for effective response and mitigation efforts.
The primary objective of this project is to develop two integrated frameworks: the Response Team Framework and the Public Engagement Framework, to address critical issues in disaster management. 
These frameworks aim to mitigate the lack of information regarding the impact of national crises and ensure that resources are appropriately allocated.

By developing these frameworks, the project aims to enhance disaster preparedness and response strategies, improve resource management, and ensure effective public communication. Ultimately, this will improve overall resilience 
and response capabilities during national crises.

# DESIGN AND PROJECT DESCRIPTION

## Response Team Framework

The core of our approach lies in empowering response teams with actionable insights extracted from diverse data streams including news reports, social media discourse, and direct communication channels. 
Utilising state-of-the-art Large Language Models (LLMs) Mistral-7B-Instruct model , our methodology involves parsing through news reports and social media posts to extract important information, with which we distil comprehensive lists of essential items required by rescue teams. 
Furthermore, we employ LLMs to succinctly summarise the overall situation, identifying crucial inventory needs and assessing the potential requirement for medication.

In addition to text analysis, a primary challenge within the Response Team Framework is the lack of accurate and detailed information available from internet sources. 
To address this issue, we propose recording voice calls from the affected population.
By utilizing speech-to-text technology, these recordings are converted into text, which is then processed by Large Language Models (LLMs). 
This approach enables us to obtain more precise and comprehensive information, thereby enhancing the accuracy and effectiveness of our response efforts.


![response3](https://github.com/user-attachments/assets/64a37808-3b2c-485a-938e-cc118e3cad5c)

The workflow depicted in the flowchart outlines a comprehensive strategy for leveraging AI to support a response team during a natural crisis. The entire Response team framework comprises three processes that will aid the response team.
Here’s a step-by-step explanation of the process:
1. The framework will first scrap the entire internet and try to find any relevant news article, reports or social media posts that contains information regarding the national crisis
2. Some critical information may not be available on the internet, news, or social media. This gap is addressed by the direct input from the callers. People affected by the incident call the response team to provide firsthand information about the crisis.
   These information prove to be vital, these information are extracted and given to the large language model to fill the gap in the information scraped from the internet.
3. The next part of the response team framework is the time series model which can predict the depletion of resources (eg. Food packages, medical supplies) as the population affected increases over the time.
   Using Autoregressive Integrated Moving Average(ARIMA) algorithm I’m trying to predict the days, months and weeks till depletion.

## Public Engagement Framework

Most individuals affected by natural disasters or national crises have unique and personal issues they wish to discuss with the response team.
However, the limited number of response team members and their constrained timeframes make it impractical to conduct one-on-one sessions with everyone in need.
To address this, I am developing a public engagement system powered by a Large Language Model (LLM). This system will guide users through the necessary steps to maximise their chances of survival, 
providing personalised assistance and ensuring that more people receive timely and relevant support.


![pub](https://github.com/user-attachments/assets/031c9671-8245-4586-a88e-c7d71e20d392)

The workflow in the flowchart outlines a system for managing public feedback during a crisis by leveraging a Large Language Model (LLM).Here’s a detailed explanation of each step in the process:
1. The system starts with input from the public, who provide feedback or report issues related to the crisis.
2. User Interaction: Users post their individual queries to an LLM, which is specifically fine-tuned or integrated with Retrieval-Augmented Generation (RAG) architecture. This integration helps in handling diverse and complex queries effectively.
3. LLM Function: The LLM processes the queries. With fine-tuning or RAG integration, the model can access a vast database of relevant information and generate accurate and contextually appropriate responses.
4. Response Generation: The LLM provides detailed solutions to the crisis-related queries. These solutions are then communicated back to the users, offering clear and actionable guidance.

# RESULTS

## RESPONSE TEAM FRAMEWORK

![Capture](https://github.com/user-attachments/assets/cead280c-99b4-4649-978e-6a22639fa80f)

![2](https://github.com/user-attachments/assets/364d1921-07c7-426a-831e-00d0845a916f)

![3](https://github.com/user-attachments/assets/232509e4-443f-40ee-8ef1-a9347072ab63)

## GENERAL PUBLIC ENGAGEMENT FRAMEWORK

![p1](https://github.com/user-attachments/assets/5c51c1c6-8764-4a26-8b94-d964adafbbd4)

![p2](https://github.com/user-attachments/assets/63b1042e-d092-474c-bdbe-1542ba624a62)




