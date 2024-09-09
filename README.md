# Tiger Analytics - Azure OpenAI Hackathon

Welcome to the Azure OpenAI hackathon organized by Microsoft in partnership with Tiger Analytics. This repository contains information (data, instructions for the workshop, and reference material) related to solutioning using Azure AI services conducted by Microsoft and Tiger Analytics.


Please feel free to reach out to the trainers during the session, for any questions or issues related to access or the
solution. We hope you have a rewarding experience during the hack event.

## Prerequisites

### Azure Account

An Azure account is necessary for resources provided in the code. You can use your organization's Azure account if available. If not create one from here: <https://azure.microsoft.com/en-us/free/>

### Operating System

Windows and Linux are the preferred operating systems for the hack event. They're preferred as the tools and libraries are tested in Windows and Linux. Macbooks can be used if there are no alternatives, but challenges are to be expected.

### Python Environment

Python version **3.9** needs to be installed on the local machine used for the hack. Refer to the instructions below to install Miniconda and create a Python 3.9 environment.

## Pre-req
pyodbc==5.1.0
python-dotenv==1.0.1
pandas==2.2.2
openai==1.34.0
jupyter==1.0.0
requests==2.32.3
azure-core==1.30.2
azure-search-documents==11.6.0b4

The Microsoft ODBC 18 driver

Azure Data Studio (optional)

### VSCode

1. If you already have an IDE setup in your system, you can skip this section
2. Install VSCode from [this website](https://code.visualstudio.com/download)
3. Install [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extensions from the VSCode marketplace
4. [Open](https://code.visualstudio.com/docs/editor/workspaces#_how-do-i-open-a-vs-code-workspace) the downloaded Source code folder in the VSCode


## Build using AI studio
Follow the mentioned [guideline](instructions/ms_hack_steps_ai_studio.pdf) to build and test RAG using azure AI studio. This step is a prerequisite to run the sdk application.


We greatly value your feedback and welcome any suggestions for improvement. Please share your thoughts [here](https://forms.office.com/r/yhjtPtAFxy). You can also scan the QR code below to provide your feedback:

[![feedback form](codes/images/README/hack_feedback_24_QR.png "Feedback form")](https://forms.office.com/r/yhjtPtAFxy)

If you have any questions, please feel free to get in touch with us at <tigernlp@tigeranalytics.com>

## Additional References

* [Refer to this GitHub repository](https://github.com/Azure/aistudio-copilot-sample)

**Note**: The Azure service accesses used in this event are only valid during the event. Please contact your respective Microsoft account teams to follow up on the continued access or further questions.
