# Product Recommendation

> Trigger: When the user asks which internship, plan, or program they should choose or requests a recommendation based on their goals.

# Steps
1. Check the customer's previous messages:
   - If they have already mentioned "AI and Data" or "AI & Data", skip directly to step 3.
   - Else, proceed to step 2.
2. Ask the customer to share their primary career goal (e.g., getting placement-ready, building a portfolio, moving into AI, or learning design) and their preferred technical interest area (e.g., Software & Cloud, AI & Data, Design & Business, or Emerging Tech).
3. Ask the customer about their weekly time commitment availability (e.g., 4-5 hours, 6-8 hours, or 9+ hours per week) and their current experience level.
4. Recommend the best matching Decode Labs program track based on their inputs:
   - **Software & Cloud** (Full Stack, Frontend, Backend, Java, Cloud Computing, DevOps, Cyber Security) — recommended for 9-11 hours/week commitment.
   - **AI & Data** (Artificial Intelligence, Python Programming, Data Science, Data Analytics, Generative AI) — recommended for 8-10 hours/week commitment.
   - **Design & Business** (UI/UX Design, Digital Marketing, Stock Market Trading, AutoCAD) — recommended for 7-9 hours/week commitment.
   - **Emerging Tech** (IoT, Blockchain, Prompt Engineering, Robotics) — recommended for 8-10 hours/week commitment.
5. Explain the key highlights of the recommended program (such as 3+ live projects, weekly milestone checkpoints, and receiving a Certificate of Completion and Letter of Recommendation).
6. Provide the pricing details for the recommended program cohort. *(No pricing retrieval tool is connected yet; pricing is based on active regional promotional cohorts.)* {{todo:high:Confirm current base pricing and promotional cohort rates for all internship tracks}}
7. Direct the customer to the {{label:Lead Qualification,id:lead-qualification,type:playbook}} playbook to capture their details and initiate the enrollment process.
