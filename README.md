# Peter Ryan – Project Portfolio

Computer Science & Business Analytics student at the University of Notre Dame.

## Featured Projects

### Amazon Health International Travel Meciation and Vaccination Eligibility Website (Contributor)
- **Tech (Frontend):** React, TypeScript, Tailwind
- **Tech (Backend):** Python (AWS Lambda, API Gateway, LangChain) 
- **Tech (Web Scraping):** Python (Beautiful Soup)
- **Tech (Vector Database):** Amazon RDS PostgreSQL + pgvector extension
- **Tech (AI Layer):** Amazon Bedrock (LLM: Nova 2 Lite; Embedding: Amazon Titan Text Embeddings V2), LangChain
- **Tech (AWS Tools):** AWS Lambda (Python), API Gateway, RDS (PostgreSQL + pgvector), Amazon Bedrock (Nova 2 Lite, Amazon Titan Embeddings v2)
- **Description:** A web app designed to let people know if certain medication can be found or is allowed to be brought into select countries as well as recommended or required vaccinations to have when traveling to those places along with resources to help accommodate anything missing or any questions the user may have
- **Repo:** [`Amazon Health International Travel Meciation and Vaccination Eligibility Website`](https://github.com/Francisco-MEB/sibc_amazon_sp26)

- **Problem:** A lot of this information is scattered and it is hard to find valid and reliable information easily when looking into medication for a trip
- **Solution:** Centralize this information along with the custoomizability and resources of Amazon Pharmacy or the Amazon Health Chatbot and many other services to bring about a more user friendly solution that is simple to use and understand

- **Challenges:**
  - Finding reliable sources and correctly formatting the scraper to pull the necessary information so it can be turned into a readable csv file
  - Working with a new database software and figuring out how to use high level PostgreSQL
 
- **What I Learned:**
  - How LLMs work and how to implement a working chatbot using RAG so that it does not hallucinate information and can pull references from a database based upon the similarity of words (or tokens) after the vectorization process

_______________________________________________________________________________________________________________

### Personal Finance Tracker
- **Tech:** Next.js, Tailwind, Bun, Hono, Drizzle, Neon, Clerk
- **Description:** A full-stack web app for tracking income, expenses, and accounts.
- **Repo:** [`Personal Financial Tracker`](https://github.com/pryan24-nd/finance-tracker)
  
- **Problem:** Most budgeting apps are opaque and inflexible. I wanted a transparent system I fully controlled.
- **Solution:** Built a full-stack web app with authentication, charts, and CSV import.

- **Technical Details:**
  - Frontend: Next.js + Tailwind
  - Backend: Hono on Edge
  - Database: Neon + Drizzle ORM
  - Auth: Clerk
  - Runtime: Bun

- **Challenges:**
  - Managing type-safe API calls across client/server
  - Production env differences on Vercel
  - Updates to React Hook Form that altered the value expected when using z.coerce.date()
  - Transitions from uncontrolled to controlled values
  - Change to arguments used in newer versions of react's useRef
  - Frontend problems with overridres from SelectTrigger

- **What I Learned:**
  - Edge runtime constraints
  - React Hook Form + Zod pitfalls
  - Production debugging on Vercel
  - How to utilize databases
  - Learned new intricacies of frontend, especially with imported tsx files and icon usage

_______________________________________________________________________________________________________________

 ### Financial NLP Analysis Website (Contributor)
 - **Tech:** Python, PyTorch, Transformers (NLP), Pandas, Web Scraping, PDF Processing
 - **Description:** A web app designed for determining whether a company is doing well using a financial document or by using stock tickers
 - **Repo:** [`Financial NLP Analysis Website`](https://github.com/mikhailsal123/financial-nlp-engine)

 - **Problem:** It is often a lengthy and involved process to determine if a company is doing well or not based on the intellectual depth of many financial statements
 - **Solution:** Use Sentiment Analysis and the FinBERT model on Hugging Face to expedite the process and make it more user friendly

 - **Challenges:**
   - Sentiment analysis only looked for words like "increase" or "grew" to determine if something was good, disregarding whether the thing increasing was a good thing
   - data that was pulled from online contained (often conflicting) information about other or competing companies besides just itself within the same document, throwing off the sentiment value

 - **What I Learned:**
   - How to work with APIs
   - How to use economic-direction scoring to create a second layer to sentiment analysis to determine if an increase in the thing being asked about is actually good
   - How to pull related information, like company name, people in charge, etc…, from company's website to determine relevant information for analysis
