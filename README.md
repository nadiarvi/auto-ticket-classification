# Automatic Customer Ticket Classification

This is the repository for Team 3 for CS372 Natural Language Processing with Python in KAIST.

## Introduction

Customer service is a cornerstone of any successful business. However, as a company grows and customer queries increase, efficiently managing and responding to support tickets can pose a significant challenge. A large volume of incoming tickets, particularly when their topic is unclear, makes the process time-consuming and cumbersome. Representatives often have to open and evaluate each ticket to comprehend its topic manually, slowing response times and reducing overall efficiency.

Many companies seek to streamline this process by categorizing tickets into specific problem classes such as 'Issue', 'Refund', and 'Feedback'. For instance, the ticket stating "Why won't the app open?" can be classified under 'Issue', while "Please cancel my subscription" falls under 'Refund', and "This is a terrible app!" is categorized as 'Feedback'. While this categorization aids in handling tickets, it is not without its challenges.

There are two predominant strategies for ticket classification: manual tagging by a customer service agent and self-categorization by the customer. Both methods, however, come with inherent disadvantages. Manual tagging requires agents to sift through potentially lengthy explanations that may only pertain to a single topic, thus resulting in delayed responses. Conversely, self-categorization risks customers misunderstanding or miscategorizing their own issues, leading to inaccurate classification and potential delays in resolution.

To overcome these challenges, this project introduces an automated approach for ticket classification using Natural Language Processing (NLP) with Python's NLTK library. We aim to enhance the ticket-handling process by accomplishing four objectives: identifying the main topic of the complaint, recognizing the product referenced, suggesting an appropriate response type, and generating a succinct summary of the complaint. This automated process is designed to boost response efficiency. Once a customer submits their complaint, the system will classify the ticket and direct it to the appropriate agent. Furthermore, this approach could potentially facilitate automated resolution for trivial issues, thereby reducing the need for human intervention. This method is envisioned to significantly improve customer ticket categorization, resolution efficiency, and accuracy.
