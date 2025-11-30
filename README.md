AWS Knowledge API

This repository contains the backend API for my personal AI assistant, web chat, Slack bot, and automation integrations.

Initial Components (to be built in later phases)

1. Lambda Functions

- askKnowledgeHandler  
  Queries Amazon Q Business or Bedrock Knowledge Base to retrieve relevant information.

- logEventHandler  
  Logs learning entries, job applications, and progress to DynamoDB.

- webChatHandler  
  Handles messages from the chat widget on my portfolio site.

- contactMeHandler  
  Sends messages submitted via the portfolio site to SES and forwards them to Gmail.

2. API Gateway Routes (planned)

POST /ask_knowledge  
POST /log_event  
POST /webchat  
POST /contact  

3. Infrastructure (future)

- AWS CDK or CloudFormation templates  
- IAM roles and permissions  
- API Gateway and Lambda integration configuration  

4. Additional Functions (future)

- smsInboundHandler  
- connectSmsHandler  
- contactLensProcessor  
- qaSummaryHandler  
- wfmSummaryHandler  

This repo will power the entire backend for my AI-driven ecosystem.
