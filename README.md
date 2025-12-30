# Peter Ryan – Project Portfolio

Computer Science & Business Analytics student at the University of Notre Dame.

## Featured Projects

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
