# C8-CRUNCH-LABS-WEB-DEV Introduction to HTML, CSS, and JavaScript 📱💻

> A free, hands-on introduction to web development — build and deploy responsive, interactive websites with HTML, CSS, and JavaScript, plus Git/GitHub and the DOM.

Welcome to the **C8 - Web Development Section 1** course, hosted by the **Code Crunch Learner Organization** at **Florida International University**! 🐯 This course will teach you the foundational skills needed to build and launch your own websites using HTML, CSS, and JavaScript, with some fun interactive elements! 🚀

## Course Overview 🎓
This **hybrid** course will introduce you to the essentials of web development, from creating simple web pages to building interactive, responsive websites. Whether you're looking to start a career in tech or just interested in learning how the web works, this is the course for you!

By the end of the course, you’ll be able to:
- Understand and use **HTML**, **CSS**, and **JavaScript** to create functional websites 🌍.
- Use tools like **Git/GitHub** for version control 🔄.
- Make your websites **responsive** and mobile-friendly 📱.
- Add interactivity to your pages using **JavaScript** and the **DOM** ✨.
- Build and deploy a portfolio website 🚀!

## Standards & equivalency

> C8 stands in for a university's web development course.

**University equivalent.** Web Development — `COP 4813`, `CS 4241`, `CIS 3319`. Coverage: full. Every outcome those sections list is taught here, assigned, and mapped to a week in the table below.

C8 carries no credit, no transcript entry, no accreditation and no proctored exam. The equivalence is one of **content and skill**: what an accredited section of that course teaches, taught here at the same depth or deeper, and assessed by work the learner submits. A registrar record is not something an open repository can give you.

| University outcome | Where this course teaches it | Depth |
| --- | --- | --- |
| Author standards-compliant HTML documents with correct semantic markup, and validate them | [Week 01](curriculum/week-01-semantic-html/) | deeper |
| Apply CSS to control presentation — the cascade, selectors, specificity, the box model, colour and typography | [Week 02](curriculum/week-02-modern-css/) | deeper |
| Produce responsive layouts that adapt across the range of devices people actually browse on | [Week 03](curriculum/week-03-layout-responsiveness/) | deeper |
| Program in JavaScript — types, operators, control flow, functions, scope and modules | [Week 04](curriculum/week-04-javascript-fundamentals/) | same |
| Manipulate the document object model and handle browser events to make a page interactive | [Week 05](curriculum/week-05-dom-events-accessibility/) | deeper |
| Collect input through HTML forms and validate it on the client before it is submitted | [Week 06](curriculum/week-06-forms-validation/) | deeper |
| Use a client-side toolchain and compose an interface from reusable components | [Week 07](curriculum/week-07-build-tools-and-components/) | deeper |
| Build a client-side application with navigation between views and managed application state | [Week 08](curriculum/week-08-state-management-and-routing/) | deeper |
| Measure and improve the performance of a page in the browser | [Week 09](curriculum/week-09-performance-and-web-vitals/) | deeper |
| Apply authentication and authorization to a web client, and recognise the common web security risks | [Week 10](curriculum/week-10-auth-and-identity/) | deeper |
| Test a web application, and use development tooling to find and diagnose defects | [Week 11](curriculum/week-11-testing-vitest-playwright/) | deeper |
| Explain HTTP and the client-server model, and deploy a working site to a public host | [Week 12](curriculum/week-12-capstone-production-spa/) | deeper |

Every row points at a week that **assigns work** on that outcome — exercises, a challenge, homework, a quiz item and a mini-project — not a week that merely mentions it.

**The industry bar.** What an employer expects of somebody paid to build for the browser, and where this course makes the learner do it.

| What the job expects | Where this course does it |
| --- | --- |
| Work lands as a commit in a repository you own, not a folder on your desktop | [`curriculum/week-01-semantic-html/mini-project/README.md`](curriculum/week-01-semantic-html/mini-project/README.md) — the Week 1 deliverable is a public repository pushed to GitHub, and every later week builds on that same repository |
| You read code you did not write and form a judgement on it | [`curriculum/week-01-semantic-html/exercises/exercise-02-fix-the-bad-html.md`](curriculum/week-01-semantic-html/exercises/exercise-02-fix-the-bad-html.md) — a broken page to diagnose in Week 1; and in Week 9 a page built slow on purpose that the learner must profile and repair, in [`curriculum/week-09-performance-and-web-vitals/mini-project/README.md`](curriculum/week-09-performance-and-web-vitals/mini-project/README.md) |
| Tests exist, and the command to run them is written down | [`curriculum/week-11-testing-vitest-playwright/mini-project/README.md`](curriculum/week-11-testing-vitest-playwright/mini-project/README.md) — a Vitest unit suite, a Testing Library component suite and a Playwright end-to-end suite, with the commands in the lecture notes beside it |
| A pipeline runs the suite on every push, and a red pipeline blocks the ship | [`curriculum/week-12-capstone-production-spa/exercises/exercise-03-ci-gates-and-lighthouse-budget.md`](curriculum/week-12-capstone-production-spa/exercises/exercise-03-ci-gates-and-lighthouse-budget.md) |
| Dependencies are declared and isolated per project, and the toolchain is the one a team uses | [`curriculum/week-07-build-tools-and-components/exercises/exercise-01-bootstrap-a-vite-app.md`](curriculum/week-07-build-tools-and-components/exercises/exercise-01-bootstrap-a-vite-app.md) — npm, a lockfile, a Vite config, and a bundle the learner has to account for byte by byte |
| You read the browser's own output rather than guessing | [`curriculum/week-12-capstone-production-spa/lecture-notes/02-security-headers-and-csp-in-anger.md`](curriculum/week-12-capstone-production-spa/lecture-notes/02-security-headers-and-csp-in-anger.md) quotes the console's real Content-Security-Policy violations, and [`curriculum/week-04-javascript-fundamentals/lecture-notes/02-scope-closures-and-modules.md`](curriculum/week-04-javascript-fundamentals/lecture-notes/02-scope-closures-and-modules.md) quotes the real temporal-dead-zone `ReferenceError`. This is uneven and we say so: C8 carries no `Common bugs to catch` block on every page. What it has instead is a `Common pitfalls` or `Common mistakes` section on the Week 7 to Week 12 project and exercise pages, written in prose |
| Your accessibility claims survive an audit somebody else runs | [`curriculum/week-05-dom-events-accessibility/README.md`](curriculum/week-05-dom-events-accessibility/README.md) — keyboard-only testing, axe DevTools, a screen reader, and a WCAG 2.2 AA Success Criterion cited for each decision, from Week 1 onward |
| It runs from a clean clone, and the README is written for a stranger | [`curriculum/week-12-capstone-production-spa/lecture-notes/03-ci-cd-and-the-portfolio-readme.md`](curriculum/week-12-capstone-production-spa/lecture-notes/03-ci-cd-and-the-portfolio-readme.md) |
| The professional task is named, not implied | the `## Standards this week meets` block in all twelve week READMEs |

**Beyond both bars.** Clearing the two floors is entry, not success. Open any of these and check it in under a minute.

| What we add | Which bar it beats | Where it lives |
| --- | --- | --- |
| Every week's quiz publishes its answer key in the same file, folded under the questions — nothing withheld until a deadline | both | [`curriculum/week-03-layout-responsiveness/quiz.md`](curriculum/week-03-layout-responsiveness/quiz.md) |
| The second half of the course ships a worked solution document for its exercises, carrying the reasoning and not only the code | both | [`curriculum/week-09-performance-and-web-vitals/exercises/SOLUTIONS.md`](curriculum/week-09-performance-and-web-vitals/exercises/SOLUTIONS.md) |
| The grading rubric is published with the project, before the work is done, so a learner can grade their own submission line by line | university | [`curriculum/week-11-testing-vitest-playwright/mini-project/starter/rubric.md`](curriculum/week-11-testing-vitest-playwright/mini-project/starter/rubric.md) |
| Performance is a measured budget rather than advice: profile the page, name the worst vital, apply the fix, re-profile, and hold LCP, INP and CLS to published thresholds | both | [`curriculum/week-09-performance-and-web-vitals/mini-project/README.md`](curriculum/week-09-performance-and-web-vitals/mini-project/README.md) |
| Identity is built from the specification rather than from a signup button — the authorization-code flow with PKCE against a Keycloak realm the learner stands up, with refresh-token rotation and reuse detection | university | [`curriculum/week-10-auth-and-identity/`](curriculum/week-10-auth-and-identity/) |
| The learner ends holding a public URL, a public repository, a passing pipeline and a recorded walkthrough of both — not a grade only a registrar can read | both | [`curriculum/week-12-capstone-production-spa/`](curriculum/week-12-capstone-production-spa/) |

**Gaps we declare.** None against the web-development outcome set — every outcome in the table above is taught and assigned. Two things are worth saying plainly anyway. C8 uses Git and GitHub from the first week's submission onward but carries no unit of its own on Git; the commands are given at the point of use, and a learner who wants version control taught properly should take it where it is taught properly. And C8 is a client-side course: it consumes APIs, deploys static builds and secures the browser end of an identity flow, but it does not teach server-side programming, database design or API authorship, and it does not claim them.

## Course Information 📚

- **Course Format**: Hybrid (Mix of in-person and online learning)
- **Classroom Location**: Available upon request
- **Class Days & Time**: Thursdays from 3:00 PM - 4:00 PM
- **Instructor**: [Instructor Name]  
- **Semester**: Spring 2024

Please review the **Florida International University Learner Handbook** for more details on conduct, academic policies, and expectations.

## Key Technologies You’ll Learn 🌐
- **HTML**: Building the structure of web pages (e.g., headings, images, links)
- **CSS**: Styling pages and making them beautiful (e.g., colors, fonts, layout)
- **JavaScript**: Adding interactivity to web pages (e.g., forms, animations, event handling)
- **Git/GitHub**: Version control to track and manage changes to your code
- **Vercel**: Deploying your website to the web 🌍

## Course Competencies 💡
By the end of the course, you’ll be able to:
- Understand core **HTML**, **CSS**, and **JavaScript** concepts.
- Use **Git** and **GitHub** for version control and collaboration.
- Create **responsive websites** that look great on any device.
- Manipulate the **DOM** to interact with webpage elements dynamically.
- Build simple **interactive web apps** using forms, animations, and event listeners.

## Weekly Breakdown 📅

| Week | Topics 🗣️                           | Coding Labs 💻                     | Learning Outcomes ✅                 |
|------|--------------------------------------|------------------------------------|--------------------------------------|
| **Week 0** | Intro to Web Development: HTML, CSS, JS | Project setup, Basic HTML page     | Understand web development tools & roles |
| **Week 1** | HTML Basics: Elements, Attributes    | Add titles, headings, images, links | Learn HTML tags and semantic HTML    |
| **Week 2** | CSS Fundamentals: Styling            | Apply CSS styles (colors, fonts)   | Understand selectors and styling     |
| **Week 3** | Flexbox & Layout Responsiveness       | Create navigation, Flexbox layout  | Learn Flexbox for layout control     |
| **Week 4** | JavaScript Basics: Variables & Functions | Basic DOM manipulation             | Learn JS syntax & DOM interaction    |
| **Week 5** | Forms & Events                       | Create forms, handle validations   | Validate forms & handle events       |
| **Week 6** | Loops & Conditionals                 | Add dynamic content                | Use loops & conditionals in JS       |
| **Week 7** | Animations & Advanced DOM            | Add animations & interactive elements | Enhance website interactivity        |
| **Week 8** | Advanced JS: Functions, Async JS     | Refactor code, Async patterns      | Master higher-order functions & async|
| **Week 9** | Advanced CSS: Grid & Layouts         | Build complex layouts with CSS Grid| Master advanced layout techniques    |
| **Week 10** | JS DOM Manipulation & Events         | Dynamic content, form validation   | Deepen JS & DOM manipulation skills |
| **Week 11** | Demo Day: Present Your Project       | Present project on GitHub, deploy to Vercel | Polish and present your final project |

## Key Milestones 🏆

- **Milestone #1** (Week 1): Basic webpage structure with HTML.
- **Milestone #2** (Week 4): Add initial CSS styling and JavaScript interactivity.
- **Milestone #3** (Week 7): Complete website with animations and interactivity.
- **Milestone #4** (Week 8): Polished website with advanced features and styling.

## Potential Final Project Ideas 💡

- **Portfolio Website**: Showcase your personal projects and skills.
- **Interactive Quiz App**: A quiz with dynamic scoring and feedback.
- **Event Landing Page**: A mobile-friendly page with registration forms.

## Learning Materials 📖
There is no required textbook for this course. However, we’ll use free online resources:
- **MDN Web Docs** (for HTML, CSS, JS reference)
- **CSS-Tricks** (for layout techniques and CSS best practices)

## Required Tools 🛠️
- **Computer with internet access**
- **Web browser** (Chrome, Edge, Safari recommended)
- **Code Editor**: Visual Studio Code (VS Code is highly recommended)
- **GitHub**: Free account for version control
- **Vercel**: Free account for deploying your projects

## GitHub & Vercel Deployment Guide ⚙️

### GitHub Setup:
1. Create a **GitHub** repository for your project.
2. Clone it to your local machine and use Git to track changes.
3. Commit and push changes regularly!

### Vercel Setup:
1. Sign up for **Vercel** and link it to your GitHub account.
2. Deploy your project by connecting your GitHub repository.
3. Every time you push to GitHub, Vercel automatically redeploys your site!

### Live Deployment 🌍:
Once your project is deployed, share the **live URL** with the class for feedback and presentations!

## Attendance 🎟️
This course is designed to be flexible. While attendance is voluntary, active participation (in both online and in-person components) will enhance your learning experience and ensure success.

## Instructor Expectations 📋
- **Respect**: Learners are expected to engage respectfully in all settings.
- **Netiquette**: Professionalism in all online communications is a must!

---

Ready to jump into web development? Let’s build something amazing together! 🌟 Feel free to reach out if you have any questions, and be sure to check out the **syllabus** for more details.

Let’s code! 💻🚀
