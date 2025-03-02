# Consolidated Assessments

## Assessment

### Questions

#### Question 1
- **Lesson:** Configuring SAP AI Core and SAP AI Launchpad
- **Type:** multiselect (Code: 3)
- **Question:** What is the first thing you need to do to start working with SAP AI Core?
**Options:**
  - ❌ Create a docker image
  - ✅ Provisioning of an SAP AI Core instance in SAP BTP 
  - ✅ A subscription to SAP AI Launchpad
  - ❌ Download data from S3 and create a resource group 

**Feedback:**
- **Correct:** Correct. Provisioning of an SAP AI Core instance in SAP BTP  and a subscription to SAP AI Launchpad. 

#### Question 2
- **Lesson:** Configuring SAP AI Core and SAP AI Launchpad
- **Type:** singleselect (Code: 2)
- **Question:** Where will the code for the ML pipelines be executed? 
**Options:**
  - ❌ Cloud
  - ❌ AI Launchpad
  - ✅ Docker
  - ❌ Container 

**Feedback:**
- **Correct:** Correct, docker.

#### Question 3
- **Lesson:** Configuring SAP AI Core and SAP AI Launchpad
- **Type:** multiselect (Code: 3)
- **Question:** Why does SAP AI Core use Kubernetes infrastructure to manage the containerized services?
**Options:**
  - ✅ The applications can be broken down into smaller parts
  - ❌ The applications circulate between the different containers to offload them
  - ✅ The applications can handle more load when needed
  - ✅ The applications are more widely available

**Feedback:**
- **Correct:** Correct. The applications can be broken down into smaller parts. The applications can handle more load when needed. The applications are more widely available.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Training an ML model
- **Type:** singleselect (Code: 2)
- **Question:** How can you leverage the power of GPUs for training a Machine Learning Model on SAP AI Core?
**Options:**
  - ❌ Specify an NVIDIA GPU in your python code.
  - ✅ Chose one of the resource plans that include GPU, for example, "train.l" in the training template.
  - ❌ GPUs are a scarce resource and may not be always available.
  - ❌ Kubernetes resources must be reserved via API. 

**Feedback:**
- **Correct:** Correct. Chose one of the resource plans that include GPU, for example, "train.l" in the training template.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Serving an ML Model
- **Type:** singleselect (Code: 2)
- **Question:** In which of the following ways can the costs for serving models be reduced?
**Options:**
  - ❌ When processing inference requests, Kubernetes allows to scale Model Servers on demand
  - ❌ By applying the same binary string to data used for training 
  - ❌ By sending new data to the model every quarter
  - ✅ When using the Autoscale to Zero feature, inference servers are "stopped" until the next request is received
  - ❌ Container 

**Feedback:**
- **Correct:** Correct. When using the Autoscale to Zero feature, inference servers are "stopped" until the next request is received

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Describing LLMs
- **Type:** singleselect (Code: 2)
- **Question:** Which of the following architectures is primarily used by LLMs ?
**Options:**
  - ✅ A neural network architecture knows as transformer
  - ❌ A mathematical calculator and function based on internet data known as modeler
  - ❌ Human text input combined with mathematical functions and calculator

**Feedback:**
- **Correct:** Correct. LLMs primarily used a neural network architecture knows as transformer.

#### Question 2
- **Lesson:** Describing LLMs
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following are some of the key risks associated with using LLMs in the context SAP Business AI?
**Options:**
  - ✅ Data Privacy Concerns
  - ✅ Misinterpretation of Data
  - ❌ Time-consuming calculations
  - ✅ Bias and Fairness

**Feedback:**
- **Correct:** Correct. Some of the key risks are: Data Privacy Concerns, Misinterpretation of Data, and Bias and Fairness.

#### Question 3
- **Lesson:** Describing SAP's Generative AI Strategy
- **Type:** singleselect (Code: 2)
- **Question:** What type of a setup is used for the LLMs in the context of the generative AI hub?
**Options:**
  - ❌ Hardware as a service (HaaS)
  - ✅ Software as a service (SaaS)
  - ❌ Platform as a service (PaaS)
  - ❌ Infrastructure as a service (IaaS)

**Feedback:**
- **Correct:** Correct. In the context of the generative AI hub, these models are typically used in a software as a service (SaaS) setup, where they are trained and hosted in the cloud and can be integrated directly into applications, products, or services. 

#### Question 4
- **Lesson:** Describing SAP's Generative AI Strategy
- **Type:** singleselect (Code: 2)
- **Question:** How can businesses directly benefit from using the LLMs in the SAP AI Core?
**Options:**
  - ❌ They can only use predesigned and pretrained AI models.
  - ✅ They can receive tailored responses or forecasts.
  - ❌ They do not need to integrate the models into their applications.
  - ❌ They do not need to input their unique data into the AI model.

**Feedback:**
- **Correct:** Correct. Businesses can directly input their unique data into the AI model and receive tailored responses or forecasts, without having to learn how to design and train an AI model.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Starting From Ideation to Productization
- **Type:** singleselect (Code: 2)
- **Question:** What is the main focus of the Ideation phase in SAP's product development process?
**Options:**
  - ❌ Finalizing the pricing model for new products
  - ❌ Assessing the feasibility, desirability, and viability of LLMs
  - ✅ Identifying potential use cases for LLMs within SAP's ecosystem
  - ❌ Gathering customer feedback on developed use cases

**Feedback:**
- **Correct:** Correct. The Ideation phase is focused on identifying potential use cases for LLMs within SAP's ecosystem. 

#### Question 2
- **Lesson:** Starting From Ideation to Productization
- **Type:** singleselect (Code: 2)
- **Question:** What is a key focus area in the Validation Phase for data engineers and software architects?
**Options:**
  - ❌ Pricing and commercialization
  - ❌ Commercial aspect of the product
  - ✅ Technical evaluation and architectural guidelines
  - ❌ Real-world usage data and customer feedback

**Feedback:**
- **Correct:** Correct. In the Validation Phase, data engineers and software architects focus on ensuring access to data for evaluation, testing various models, and following architectural guidelines defined for their use case.

#### Question 3
- **Lesson:** Integrating LLMs into Business Applications
- **Type:** singleselect (Code: 2)
- **Question:** Which data framework is designed for developing data-aware applications powered by LLMs?
**Options:**
  - ✅ LangChain
  - ❌ LlamaIndex
  - ❌ SAP BTP
  - ❌ GPT Index

**Feedback:**
- **Correct:** Correct. LangChain is a framework designed for developing data-aware applications powered by LLMs.

#### Question 4
- **Lesson:** Integrating LLMs into Business Applications
- **Type:** singleselect (Code: 2)
- **Question:** What is emphasized in the integration of frameworks, such as LangChain and LlamaIndex, in LLM application development using SAP's methodical approach?
**Options:**
  - ❌ Technical feat
  - ✅ Strategic orchestration
  - ❌ User experienced
  - ❌ Data intelligence

**Feedback:**
- **Correct:** Correct. The integration of frameworks, such as LangChain and LlamaIndex, is not just a technical feat; it's a strategic orchestration of data, intelligence, and user experience.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Identifying the Appropriate Optimization Technique for Different LLM Use Cases
- **Type:** singleselect (Code: 2)
- **Question:** Which of the following is the first step in the optimization journey for improving LLM performance?
**Options:**
  - ❌ Adding few-shot examples
  - ❌ Model fine-tuning
  - ❌ Integrating more context from a live knowledge base
  - ✅ Prompt engineering and evaluation 

**Feedback:**
- **Correct:** Correct. The optimization journey begins with prompt engineering and an evaluation to establish a baseline. This step is crucial for identifying whether performance issues are related to context or the model's behavior, setting the foundation for further optimization techniques. 

#### Question 2
- **Lesson:** Identifying the Appropriate Optimization Technique for Different LLM Use Cases
- **Type:** singleselect (Code: 2)
- **Question:** Which of the following methods is often the go-to method when relevance and reliability are crucial, and there is adequate context available for your LLM use case?
**Options:**
  - ✅ RAG approach
  - ❌ Model fine-tuning
  - ❌ Few-shot examples
  - ❌ Adding a fact-checking step

**Feedback:**
- **Correct:** Correct. The RAG approach is preferred when relevance and reliability are key, and there is already adequate context. It is a method that helps you improve the output by integrating more contextual information without extensive model fine-tuning.

#### Question 3
- **Lesson:** Understanding Principles of Prompt Engineering
- **Type:** singleselect (Code: 2)
- **Question:** What is the primary goal of prompt engineering when working with LLMs?
**Options:**
  - ❌ To reduce the computational cost of training LLMs
  - ✅ To guide the model towards generating the desired output
  - ❌ To increase the size of the training dataset
  - ❌ To simplify the model's architecture

**Feedback:**
- **Correct:** Correct. Prompt engineering is essential for crafting inputs that lead the model to produce outputs aligned with specific goals. It involves creating clear, specific prompts that guide the model effectively.

#### Question 4
- **Lesson:** Understanding Principles of Prompt Engineering
- **Type:** singleselect (Code: 2)
- **Question:** What is the main purpose of the CoT and ToT techniques in relation to LLMs?
**Options:**
  - ❌ To limit the depth and quality of LLM responses
  - ✅ To improve the depth and quality of LLM responses
  - ❌ To restrict LLMs from exploring multiple lines of reasoning
  - ❌ To decrease the models' understanding of conversation context

**Feedback:**
- **Correct:** Correct. The main purpose of the CoT and ToT techniques is to improve the depth and quality of LLM responses.

#### Question 5
- **Lesson:** Understanding Principles of Prompt Engineering
- **Type:** singleselect (Code: 2)
- **Question:** How does the ToT technique differ from the CoT technique?
**Options:**
  - ❌ ToT is a linear, guiding the model through a single chain of reasoning steps to reach a conclusion.
  - ❌ CoT involves presenting multiple related prompts in a linear chain.
  - ✅ ToT allows the model to handle different strands of thought simultaneously, similar to branches on a tree.
  - ❌ CoT creates a branching structure for exploring different paths in a conversation.

**Feedback:**
- **Correct:** Correct. The Tree-of-Thought (ToT) technique allows the model to handle different strands of thought simultaneously, similar to branches on a tree. The Chain-of-Thought (CoT) technique involves presenting multiple related prompts in a linear chain.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Identifying RAG Use Cases
- **Type:** singleselect (Code: 2)
- **Question:** What is the primary goal of the Retrieval Augmented Generation (RAG) approach?
**Options:**
  - ❌ To reduce the size of large language models
  - ❌ To eliminate the need for any external knowledge base
  - ✅ To provide the model access to up-to-date, domain-specific information
  - ❌ To simplify the model's architecture

**Feedback:**
- **Correct:** Correct. RAG aims to augment a large language model's capabilities by integrating it with a retrieval system, allowing access to a broader range of up-to-date, domain-specific information. This enhances the model's responses by making them more accurate and relevant.

#### Question 2
- **Lesson:** Identifying RAG Use Cases
- **Type:** singleselect (Code: 2)
- **Question:**  What is the SAP HANA Cloud vector engine designed to handle?
**Options:**
  - ❌ Structured data
  - ✅ Unstructured vector data
  - ❌ Text data
  - ❌ Image data

**Feedback:**
- **Correct:** Correct. The SAP HANA Cloud vector engine is designed to handle complex and unstructured vector data.

#### Question 3
- **Lesson:** Identifying RAG Use Cases
- **Type:** singleselect (Code: 2)
- **Question:** How does the SAP HANA Cloud vector engine add more context to generative AI scenarios?
**Options:**
  - ❌ By processing and comparing vector data 
  - ✅ By storing and analyzing vector embeddings
  - ❌ By integrating frameworks like LangChain
  - ❌ By providing a high-performance vector store

**Feedback:**
- **Correct:** Correct. The SAP HANA Cloud vector engine adds more context to generative AI scenarios by storing and analyzing vector embeddings. 

#### Question 4
- **Lesson:** Introducing Fine-Tuning
- **Type:** singleselect (Code: 2)
- **Question:** What is the primary purpose of fine-tuning a Large Language Model (LLM)?
**Options:**
  - ❌ To introduce new knowledge to the model
  - ❌ For quick iterations on a new use case
  - ✅ To customize the model for specific tasks by continuing the training process on a new data set
  - ❌ To reduce the size of the model for easier deployment

**Feedback:**
- **Correct:** Correct. Fine-tuning continues the training of an existing model on a new, often more domain-specific data set, transforming a general model into one better suited for specific tasks. Fine-tuning is aimed at customizing and improving an existing model's performance on specific tasks.

#### Question 5
- **Lesson:** Introducing Fine-Tuning
- **Type:** singleselect (Code: 2)
- **Question:** When is fine-tuning not ideal?
**Options:**
  - ✅ When introducing new knowledge to a model
  - ❌ When providing quick iterations on a new use case
  - ❌ When customizing outputs for specific types of inputs
  - ❌ When eliminating harmful content

**Feedback:**
- **Correct:** Correct. Fine-tuning is not ideal for introducing new knowledge or for quick iterations on a new use case due to the slower feedback loop and substantial investment in creating datasets.

#### Question 6
- **Lesson:** Optimizing LLM Performance Using Agents
- **Type:** singleselect (Code: 2)
- **Question:** What role do agents play in optimizing Large Language Model (LLM) performance?
**Options:**
  - ✅ They act as bridges between humans and LLMs, translating user input into prompts and interpreting outputs.
  - ❌ They provide additional data sources and perform complex calculations.
  - ❌ They are used to debug and inspect LLM output.
  - ❌ They enhance the user experience by offering code completion.

**Feedback:**
- **Correct:** Correct. Agents serve as intermediaries between humans and LLMs, translating user input into prompts that LLMs can understand and interpreting the output of LLMs back into natural language.

#### Question 7
- **Lesson:** Optimizing LLM Performance Using Agents
- **Type:** multiselect (Code: 3)
- **Question:** What do functions do in the context of LLMs?
**Options:**
  - ❌ Translate user input into prompts for LLM
  - ✅ Provide access to external data sources
  - ✅ Improve the performance of LLM on specific use cases
  - ❌ Manage the interaction between user and LLM

**Feedback:**
- **Correct:** Correct. Functions are small units of code that provide LLMs with other capabilities, such as access to external data sources or performing complex calculations, significantly improving the performance of LLMs on specific use cases.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Evaluating and Testing Your LLM Use Case
- **Type:** singleselect (Code: 2)
- **Question:** Which metric helps avoid false positives?
**Options:**
  - ❌ F1 Score
  - ✅ Precision
  - ❌ Recall
  - ❌ Classification Accuracy

**Feedback:**
- **Correct:** Correct. Precision quantifies how many of the predicted positive instances are actually positive, thus helps avoid false positives.

#### Question 2
- **Lesson:** Evaluating and Testing Your LLM Use Case
- **Type:** singleselect (Code: 2)
- **Question:** What is not a common capability explored at inference time?
**Options:**
  - ❌ Sentiment Analysis
  - ❌ Named entity recognition
  - ✅ Fine-tuning on domain-specific data
  - ❌ Language translation

**Feedback:**
- **Correct:** Correct. Fine-tuning the model on domain specific data is part of the model training process, not a capability used during inference time.

#### Question 3
- **Lesson:** Evaluating and Testing Your LLM Use Case
- **Type:** singleselect (Code: 2)
- **Question:** What is the impact of incremental updates to LLM training data?
**Options:**
  - ❌ Reduces the need for failover policies
  - ❌ Reduces the role of MLOps
  - ✅ Maintains performance as new data comes in
  - ❌ Increases the need for benchmarking

**Feedback:**
- **Correct:** Correct. Incrementally updating training data with new product specifications, policy documents, and so on, can help continually fine-tune LLMs and maintain performance as new data comes in.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Welcoming You to Explore Business AI with SAP
- **Type:** multiselect (Code: 3)
- **Question:** Why is it critical to continuously learn and adapt in the field of AI?
**Options:**
  - ❌ AI is a hype topic everyone should know about.
  - ❌ AI is already a major part in controlling every company.
  - ✅ AI is one of the most transformative technologies of our times.
  - ✅ AI is one of the most fast paced technology disruptions.

**Feedback:**
- **Correct:** Correct! As a matter of fact, AI is one of the most transformative technologies of our times and in addition to that, AI is one of the most fast paced technology disruptions.

#### Question 2
- **Lesson:** Summarizing AI
- **Type:** multiselect (Code: 3)
- **Question:** What are some examples of AI?
**Options:**
  - ✅ Unlocking your cell phone using facial recognition
  - ❌ Receiving counted money at the cash terminal
  - ✅ Auto completion of sentences when writing an email
  - ❌ Getting a printed ticket from the ticket machine

**Feedback:**
- **Correct:** Correct! Some examples of AI are unlocking your cell phone using facial recognition and auto completion of sentences when writing an email. The other options are simply machines.

#### Question 3
- **Lesson:** Summarizing AI
- **Type:** singleselect (Code: 2)
- **Question:** Having recapped AI, which of these statements apply?
**Options:**
  - ❌ Machine Learning is a technology which encompasses AI, deep learning and generative AI.
  - ❌ Deep Learning is a technology which encompasses AI, machine learning, and generative AI.
  - ✅ AI is a technology which encompasses machine learning, deep learning and generative AI.
  - ❌ Generative AI is a technology which encompasses AI, machine learning, and deep learning.

**Feedback:**
- **Correct:** Correct! In fact, AI is a technology which encompasses machine learning, deep learning and generative AI.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Discovering the Fundamentals of SAP Business AI
- **Type:** multiselect (Code: 3)
- **Question:** What are the key requirement properties for SAP's AI in business?
**Options:**
  - ✅ Relevant
  - ✅ Reliable
  - ❌ Replicable
  - ❌ Restrictive
  - ✅ Responsible

**Feedback:**
- **Correct:** Correct! The key requirements for AI are Relevant, Reliable, and Responsible.

#### Question 2
- **Lesson:** Transforming Business Applications and Platform with Generative AI
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following allow SAP Business AI to distinguish between embedded AI and extensibility approaches within its solution portfolio?
**Options:**
  - ✅ By providing a clear legal framework
  - ✅ By offering all-in-one contracts
  - ❌ By offering embedded AI credits in all solutions
  - ✅ By collaborating with a wide ecosystem of partners

**Feedback:**
- **Correct:** Correct! This ensured by providing a clear legal framework, by offering all-in-one contracts, and by collaborating with a wide ecosystem of partners.

#### Question 3
- **Lesson:** Building on a Trusted AI Foundation
- **Type:** multiselect (Code: 3)
- **Question:** Which approaches in SAP BTP ensure that generative AI grounds and adapts to business context?
**Options:**
  - ✅ Prompt engineering tools and templates
  - ❌ Integration to ChatGPT
  - ✅ Vector engine in SAP HANA Cloud
  - ✅ Fine-tuned models on specific scenarios
  - ❌ Adaptive search engine in SAP S/4HANA Cloud Public Edition

**Feedback:**
- **Correct:** Correct! This is fulfilled by innovative approaches in SAP BTP to ground and adapt generative AI to business context, such as a vector engine in SAP HANA Cloud, fine-tuned models on specific scenarios, and "prompt engineering" tools and templates.

#### Question 4
- **Lesson:** Using SAP Business AI Responsibly
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following are key pillars of SAP's ethical AI framework announced in 2018?
**Options:**
  - ❌ Foreseeableness and Simplicity
  - ✅ Transparency and Explainability
  - ✅ Human Agency and Oversight
  - ❌ Robustness and Performance
  - ✅ Addressing Bias and Discrimination

**Feedback:**
- **Correct:** Correct! Ethical AI at SAP is grounded in human agency and oversight, addressing bias and discrimination, transparency and explainability, and fostering a free, civic society that empowers humans.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Getting to Know Joule, SAP's Next-Generation AI Copilot
- **Type:** singleselect (Code: 2)
- **Question:** What is special about Joule?
**Options:**
  - ❌ Joule is faster than any alternative.
  - ✅ Joule understands business.
  - ❌ Joule has a larger foundation than competitors.
  - ❌ Joule works deterministically.

**Feedback:**
- **Correct:** Correct! Joule is an advanced, generative AI copilot that truly understands business and with this, will transform the way businesses run.

#### Question 2
- **Lesson:** Getting to Know Joule, SAP's Next-Generation AI Copilot
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following characteristics apply to Joule?
**Options:**
  - ❌ Joule only works with SAP data sources.
  - ✅ Users interact with Joule in plain language.
  - ✅ SAP Build Code is a Joule add-on for code generation.
  - ❌ SAP Joule was first launched for SAP Ariba and Concur.

**Feedback:**
- **Correct:** Correct! In fact, Users interact with Joule in plain language and SAP Build Code is a Joule add-on for code generation.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Getting Familiar with AI Foundation
- **Type:** singleselect (Code: 2)
- **Question:** How could you describe AI Foundation?
**Options:**
  - ❌ A development environment
  - ❌ An engine for coding modules
  - ❌ A collaboration platform
  - ✅ A one-stop-shop for developers

**Feedback:**
- **Correct:** Correct! Introduced at SAP TechEd in 2023, AI Foundation is a one-stop-shop for developers to bootstrap their own Business AI solutions by creating AI- and generative AI-powered extensions and applications on SAP Business Technology Platform (SAP BTP) and beyond.

#### Question 2
- **Lesson:** Outlining SAP Business AI Integration into Cloud
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following are characteristics of a custom extension?
**Options:**
  - ✅ It offers the highest level of customization and flexibility but requires significant development resources and expertise.
  - ❌ Users interact with AI features within the familiar SAP environment, providing a cohesive user experience.
  - ❌ The AI features are an integral part of the SAP Business application, enhancing its capabilities without requiring separate installations.
  - ✅ Organizations create and implement AI models and applications from scratch, leveraging SAP development tools and frameworks.

**Feedback:**
- **Correct:** Correct! Characteristics of a custom extension are 1.) Organizations create and implement AI models and applications from scratch, leveraging SAP development tools and frameworks and 2.) it offers the highest level of customization and flexibility but requires significant development resources and expertise. The other two options belong to embedded AI.

#### Question 3
- **Lesson:** Getting familiar with the AI Ecosystem Partnerships and Investments
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following are services offered by SAP’s AI Foundation?
**Options:**
  - ✅ Pre-trained AI models for common tasks like Document Information Extraction
  - ✅ Instant access to a broad range of large language models
  - ❌ Simulated User Acceptance Testing and signoff
  - ✅ Tooling for prompt engineering and experimentation

**Feedback:**
- **Correct:** Correct! Services are pre-trained AI models for common tasks like Document Information Extraction, instant access to a broad range of large language models, and tooling for prompt engineering and experimentation.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Exploring the Potential of SAP Business AI
- **Type:** singleselect (Code: 2)
- **Question:** Where can you find further information regarding specific use cases for Business AI?
**Options:**
  - ✅ On Interactive Value Journeys (IVjs).
  - ❌ On Learning.SAP.com
  - ❌ On the SAP Help portal
  - ❌ On the SAP Roadmap Viewer

**Feedback:**
- **Correct:** Correct! Through Interactive Learning Journeys (IVJs) you can find more information about specific use cases for Business AI.

#### Question 2
- **Lesson:** Exploring the Strategic Roadmap for SAP Business AI
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following are the insights provided by the AI Foundation and the SAP ecosystem, including partnerships and investment areas?
**Options:**
  - ✅ AI Foundation is a one-stop-shop for developers to bootstrap their own Business AI solutions.
  - ✅ SAP partners with leading general-purpose AI vendors and large language model providers.
  - ❌ SAP offers the resell of customer application built on SAP AI Foundation solutions.
  - ✅ SAP offers a range of options for embarking on their AI journey.

**Feedback:**
- **Correct:** Correct! In fact, the following are these insights: AI Foundation is a one-stop-shop for developers to bootstrap their own Business AI solutions, SAP partners with leading general-purpose AI vendors and large language model providers, and SAP offers a range of options for embarking on their AI journey.

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Exploring Generative AI Hub
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following tools does SAP AI Foundation provide to developers? 
**Options:**
  - ❌ Basic word processing applications 
  - ✅ Tools to develop, deploy, and manage custom-built AI applications
  - ✅ Access to frontier AI models and generative AI foundation models
  - ❌ Financial auditing tools

**Feedback:**
- **Correct:** Well done!

#### Question 2
- **Lesson:** Exploring Generative AI Hub
- **Type:** multiselect (Code: 3)
- **Question:** What advantage does generative AI hub provide over traditional AI infrastructures? 
**Options:**
  - ✅ It allows trusted LLM and foundation model access, grounded on business and context data.
  - ✅ It supports developing, deploying, and managing custom-built AI solutions.
  - ✅ It provides access to multiple large language models.
  - ❌ It saves your prompts or data automatically. 

**Feedback:**
- **Correct:** Well done! 

#### Question 3
- **Lesson:** Explaining Generative AI Hub Applications
- **Type:** multiselect (Code: 3)
- **Question:** What is the primary role of SAP’s AI Foundation? 
**Options:**
  - ❌ To manage SAP's customer accounts.
  - ✅ To extend SAP applications with AI and build custom AI solutions.
  - ✅ To help developers orchestrate cutting-edge AI technology with business context
  - ❌ To train all employees on AI

**Feedback:**
- **Correct:** Well done!

#### Question 4
- **Lesson:** Explaining Generative AI Hub Applications
- **Type:** multiselect (Code: 3)
- **Question:** In which of the following contexts can generative AI revolutionize industries ?
**Options:**
  - ❌ Replacing human workers entirely in every sector
  - ✅ Automating intricate processes
  - ❌ Solely operating based on structured schema interactions
  - ✅ Offering valuable assistance for many tasks 

**Feedback:**
- **Correct:** Well done!

#### Question 5
- **Lesson:** Developing Basic Prompts for Common Queries
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following interfaces does generative AI hub in SAP AI Launchpad offer? 
**Options:**
  - ✅ Chat
  - ❌ Document Editor
  - ✅ Prompt Editor 
  - ✅ Prompt Management

**Feedback:**
- **Correct:** Well done!

#### Question 6
- **Lesson:** Developing Basic Prompts for Common Queries
- **Type:** multiselect (Code: 3)
- **Question:** Which advantage provide open-weights LLMs? 
**Options:**
  - ✅ They reduce costs 
  - ✅ They come with community support
  - ❌ They can only be used by large enterprises
  - ✅ They prevent vendor lock-in

**Feedback:**
- **Correct:** Well done!

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Identifying the Need for Using Generative-AI-Hub-SDK
- **Type:** singleselect (Code: 2)
- **Question:** What is NOT a benefit of using SDKs for generative AI hub mentioned in the lesson?
**Options:**
  - ❌ Increased efficiency and ease of integration
  - ❌ Customization opportunities
  - ❌ Streamlined development processes
  - ✅ In-house training of new AI models

**Feedback:**
- **Correct:** Well done!

#### Question 2
- **Lesson:** Identifying the Need for Using Generative-AI-Hub-SDK
- **Type:** multiselect (Code: 3)
- **Question:** What are the benefits of using LLMs in generative AI hub? 
**Options:**
  - ✅ They can be used to enhance business user experience
  - ✅ They are appropriate for a wide range of industries
  - ❌ They can be accessed only through SDKs
  - ✅ They increase flexibility by handling multimodal inputs and outputs

**Feedback:**
- **Correct:** Well done!

#### Question 3
- **Lesson:** Using generative-AI-hub-SDK to interact with Orchestration Services
- **Type:** multiselect (Code: 3)
- **Question:** What is a key advantage of using orchestration services in generative AI hub? 
**Options:**
  - ✅ Coordinating and managing deployment and integration of AI components
  - ❌ Automated accounting and payroll services
  - ✅ Streamlining and automating the end-to-end lifecycle of AI applications
  - ❌ Manual model tuning

**Feedback:**
- **Correct:** Well done!

#### Question 4
- **Lesson:** Using generative-AI-hub-SDK to interact with Orchestration Services
- **Type:** multiselect (Code: 3)
- **Question:** In which scenario are orchestration services particularly useful in the context of the problem stated?
**Options:**
  - ✅ To avoid complex and redundant code and workflows
  - ❌ To enhance UI/UX design 
  - ✅ For seamless integration and management of diverse components like data pipelines, AI models, and prebuilt modules 
  - ❌ For video rendering

**Feedback:**
- **Correct:** Well done!

#### Question 5
- **Lesson:** Using Generative-AI-hub-SDK to Leverage the Power of LLMs
- **Type:** singleselect (Code: 2)
- **Question:** When utilizing SDK in generative AI hub, which function is primarily used to generate completions? 
**Options:**
  - ❌ Chat() 
  - ❌ Embeddings() 
  - ✅ Completions.create()
  - ❌ Prompt()

**Feedback:**
- **Correct:** Well done!

#### Question 6
- **Lesson:** Using Generative-AI-hub-SDK to Leverage the Power of LLMs
- **Type:** multiselect (Code: 3)
- **Question:** Which key component is necessary for configuring models in the generative AI hub SDK?
**Options:**
  - ✅ Client ID 
  - ✅ Authentication URL 
  - ✅ AI Core Base URL 
  - ❌ SAP ERP Instances

**Feedback:**
- **Correct:** Well done!

#### Question 7
- **Lesson:** Using Generative-AI-hub-SDK to Evaluate Prompts
- **Type:** multiselect (Code: 3)
- **Question:** Why is it important to evaluate prompts using generative AI hub SDK? 
**Options:**
  - ✅ To ensure automated and consistent evaluation across various scenarios
  - ❌ To automate all accounting processes 
  - ✅ To use objective metrics such as relevance, coherence, and fluency 
  - ❌ To enhance company annual revenue directly 

**Feedback:**
- **Correct:** Well done!

#### Question 8
- **Lesson:** Using Generative-AI-hub-SDK to Evaluate Prompts
- **Type:** singleselect (Code: 2)
- **Question:** Which evaluation function aspect is NOT implemented in the provided solution? 
**Options:**
  - ❌ RateLimitedIterator for controlling iterations
  - ❌ Evaluation function to validate JSON output
  - ❌ A final function to evaluate large datasets 
  - ✅ Financial impact analysis

**Feedback:**
- **Correct:** Well done!

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Describing Techniques for Refining Prompts
- **Type:** singleselect (Code: 2)
- **Question:** Which of these is NOT an advanced prompting method discussed in the lesson? 
**Options:**
  - ❌ One-Shot Prompting 
  - ✅ Fuzzy Prompting 
  - ❌ Few-Shot Prompting 
  - ❌ Metaprompting 

**Feedback:**
- **Correct:** Well done!

#### Question 2
- **Lesson:** Describing Techniques for Refining Prompts
- **Type:** multiselect (Code: 3)
- **Question:** Which of the following can be improved by advanced prompting refinements?
**Options:**
  - ✅ Specificity of AI outputs 
  - ✅ Overall user experience
  - ❌ Hardware performance 
  - ✅ Accuracy and relevance of responses

**Feedback:**
- **Correct:** Well done!

#### Question 3
- **Lesson:** Implementing Advanced Prompt Engineering Techniques
- **Type:** singleselect (Code: 2)
- **Question:** What does the few-shot prompting technique involve? 
**Options:**
  - ❌ Providing a single example to the model 
  - ✅ Utilizing multiple examples to guide the model
  - ❌ Using a model without examples 
  - ❌ Manual fine-tuning without context 

**Feedback:**
- **Correct:** Well done!

#### Question 4
- **Lesson:** Implementing Advanced Prompt Engineering Techniques
- **Type:** multiselect (Code: 3)
- **Question:** Which method was specifically implemented to improve prompt responses in the Facility solutions scenario? 
**Options:**
  - ✅ Few-shot prompting
  - ✅ Metaprompting
  - ❌ Inserting code snippets manually 
  - ❌ Updating the SAP ERP system

**Feedback:**
- **Correct:** Well done!

---
## Assessment

### Questions

#### Question 1
- **Lesson:** Exploring Different Large Language Models
- **Type:** multiselect (Code: 3)
- **Question:** Which benefits did generative AI hub offer for selecting different models? 
**Options:**
  - ✅ Flexible access to various models 
  - ❌ Hardware-specific integration
  - ✅ Ability to switch seamlessly between models
  - ❌ Managing financial transactions

**Feedback:**
- **Correct:** Well done!

#### Question 2
- **Lesson:** Exploring Different Large Language Models
- **Type:** multiselect (Code: 3)
- **Question:** Which models are specifically managed under the global AI scenario foundation-models? 
**Options:**
  - ✅ Azure OpenAI Service models
  - ✅ SAP AI Core models 
  - ✅ GCP Vertex AI models
  - ✅ Amazon Bedrock models 
  - ❌ WuDao models

**Feedback:**
- **Correct:** Well done!

#### Question 3
- **Lesson:** Selecting the Suitable LLM
- **Type:** multiselect (Code: 3)
- **Question:** When evaluating different models, which factors must you consider?
**Options:**
  - ✅ Cost Efficiency 
  - ✅ Scalability 
  - ❌ UI design principles
  - ✅ Flexibility

**Feedback:**
- **Correct:** Well done!

#### Question 4
- **Lesson:** Selecting the Suitable LLM
- **Type:** singleselect (Code: 2)
- **Question:** Which model is exemplified as the best proprietary OpenAI model during evaluation? 
**Options:**
  - ❌ meta--llama3-70b 
  - ✅ gpt-4o 
  - ❌ SAP HANA SQL 
  - ❌ spacy-lm

**Feedback:**
- **Correct:** Well done!

---
