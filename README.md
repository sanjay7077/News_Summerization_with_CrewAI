# News_Summerization_with_CrewAI

#Install Required Libraries(using pip) : 
--------------------------------------
Install CrewAI, LangChain, and OpenAI dependencies.
Ensure all necessary packages are available for execution.

#Set Up the OpenAI LLM:
-----------------------
Import ChatOpenAI from LangChain.
Set the OpenAI API Key as an environment variable.
Load the GPT-4o-mini model

#Initialize a Web Search Tool:
------------------------------
Import WebsiteSearchTool from crewai_tools.
Create an instance of the Web Search Tool.
This tool allows the AI agent to search for real-time AI news.\

#Create AI Agents:
------------------
Create the Researcher Agent
Create the Writer Agent

#Define Tasks for Agents:
--------------------------
Define the Research Task
Define the Writing Task

Assemble the Crew and Execute ---> crew.kickoff()
