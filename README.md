# FlowPi — AI Lead Intake & Qualification

An AI-powered n8n workflow that automates lead intake, inquiry classification, and lead qualification to help businesses manage sales opportunities efficiently.

### Key Features
- Webhook-based lead intake
- AI-powered inquiry classification using Google Gemini
- Lead qualification: Qualified, Potential, or Unqualified
- Automated routing based on qualification results

### Tech Stack
n8n · Google Gemini · Webhooks · APIs

### Setup
Import the workflow JSON into n8n, configure the required credentials, and test with sample leads.

**FlowPi** — A smarter world, together.

Website: https://www.flowpi.net


## Workflow Screenshots

![Lead Intake Workflow](Screenshot%202026-10-22%20at%2015.39.57.png)

![Lead Qualification Results](Screenshot%202026-10-22%20at%2016.18.05.png)

![Lead Qualification Details](Screenshot%202026-10-22%20at%2016.18.43.png)


# AI Email Draft Generation

An n8n workflow that uses AI to analyse incoming emails and generate relevant reply drafts for human review.

### Key Features
- Retrieves incoming email content.
- Uses AI to understand the email and draft a contextual response.
- Produces structured output for downstream processing.
- Prepares replies for human review before sending.

### Tech Stack
n8n · Google Gemini · Gmail · AI automation

### Purpose
Reduce manual email handling while keeping a human in control of outgoing communications.

# AI Email Draft Approval

An n8n workflow that supports human review and approval of AI-generated email drafts before they are sent.

### Key Features
- Presents generated drafts for human review.
- Allows a reviewer to approve or reject a draft.
- Supports controlled email sending after approval.
- Helps prevent unreviewed AI-generated replies from being sent automatically.

### Tech Stack
n8n · Gmail · Workflow automation · Human-in-the-loop approval

### Purpose
Improve email response efficiency while maintaining human oversight, accuracy, and control.

##Workflow Screenshots

# AI Chatbot with Content Guardrails

A simple AI chatbot built with n8n that generates responses while applying content safety guardrails to help prevent inappropriate or unsafe outputs.

### Key Features
- Accepts user questions through a chat interface.
- Uses an AI model to generate responses.
- Applies content guardrails to evaluate requests and responses.
- Helps restrict inappropriate or disallowed content.
- Returns responses through the chatbot interface.

### Tech Stack
n8n · LLM · AI Guardrails · Workflow Automation

### Purpose
Demonstrate how AI chatbots can combine conversational capabilities with safety checks for more controlled and responsible interactions.

### Setup
Import the workflow JSON into n8n, configure the required credentials, and test both normal and restricted requests.

##Workflow Screenshots

# AI Customer Support Chatbot with RAG

An AI-powered customer support chatbot built with n8n that uses Retrieval-Augmented Generation (RAG) to answer customer questions using information retrieved from a knowledge base.

### Key Features
- Answers customer questions using relevant knowledge base content.
- Retrieves contextual information through vector search.
- Generates AI responses grounded in retrieved information.
- Helps provide consistent and relevant customer support.
- Can be extended to support additional knowledge sources and business workflows.

### Tech Stack
n8n · LLM · RAG · Qdrant · Embeddings

### Purpose
Demonstrate how businesses can use AI and knowledge retrieval to automate customer support while reducing reliance on generic, ungrounded chatbot responses.

### Setup
Import the workflow JSON into n8n, configure the required credentials and vector database, populate the knowledge base, and test with sample customer questions.

**Workflow Screenshots

# AI Image Difference Detector Agent

An AI-powered image comparison workflow built with n8n that analyses two images to identify visual differences and generate a structured comparison report.

### Key Features
- Accepts two images for comparison.
- Uses AI vision capabilities to analyse visual differences.
- Identifies changes in objects, appearance, and image details.
- Generates a structured summary of detected differences.
- Can support visual inspection and quality-checking workflows.

### Tech Stack
n8n · AI Vision Model · Image Processing · Workflow Automation

### Purpose
Demonstrate how AI-powered image comparison can help automate visual inspections, identify changes, and support quality assurance processes.

### Setup
Import the workflow JSON into n8n, configure the required model credentials, and test with sample image pairs.

**Workflow Screenshots
