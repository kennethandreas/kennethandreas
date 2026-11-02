# Hi, I'm Kenneth Andreas

I'm an Informatics graduate from Universitas Gunadarma who builds products end to end for real users. I start from the requirements, decide what goes into the first version and what waits, then design, build, test and launch it. My recent work includes a direct booking system for a nature resort, an AI service navigator for my campus and an e-learning platform for a public elementary school. I'm open to product management and software engineering roles.

## Featured projects

### [Lingkung Gunung Resort: website and direct booking system](https://github.com/kennethandreas/lingkung-gunung-resort)

- **Problem:** The resort depended on online travel agents, which take a 15–25% commission per booking, and had no online booking channel of its own.
- **Solution:** A booking website with real-time availability, a 25% deposit option via Midtrans, a Package Builder that turns group requests into PDF proposals for the sales team, verified-only guest reviews and a full admin panel. Built solo, from requirements to deployment.
- **Impact:** Built and tested end to end: 156 automated tests pass, including one where 5 parallel processes compete for the last unit and only one booking succeeds, and the full deposit-to-paid cycle is verified in the Midtrans sandbox. Launch is waiting on the resort's production setup: email domain, live payment keys and refund policy.

### [Gunadarma Service Navigator: AI search for campus services](https://github.com/kennethandreas/gunadarma-service-navigator)

- **Problem:** Students often don't know which office or service handles their request, and keyword search only works if they already know the official term.
- **Solution:** Students ask in everyday Indonesian, and an intent classifier (TF-IDF + Naive Bayes) points them to the right service. It shows "not sure yet" instead of a wrong guess, and gives admins a feedback loop to retrain the model from real questions. Undergraduate thesis.
- **Impact:** 96.2% accuracy on a held-out test set across 10 intents. Adding Indonesian stemming raised accuracy from about 92%, and the app keeps working through keyword search when the AI service is offline.

### [Elementary School E-Learning: SDN Susukan 08 Pagi](https://github.com/kennethandreas/elementary-school-elearning)

- **Problem:** The school needed to deliver materials and assessments online in a way young children can use on their own, while keeping teachers and parents involved in each student's progress.
- **Solution:** One platform with separate portals for students, teachers, parents and admins: timed quizzes, a daily learning checklist with points and badges, and parent access with the child's student ID, with no extra account needed.
- **Impact:** Built for a real school as a Software Project Management course project, covering the full lifecycle from requirements gathering and planning to development and version control.

Other work: [TS Solution](https://github.com/kennethandreas/tssolution) (company website with a custom CMS, live at [tssolution.co.id](https://tssolution.co.id)) and [Indonesia AI Website](https://github.com/kennethandreas/indonesia-ai-website).

## Links

- Portfolio: https://kenneth-portfolio.kennethandreas12.workers.dev/
- LinkedIn: https://www.linkedin.com/in/kennethandreas/
