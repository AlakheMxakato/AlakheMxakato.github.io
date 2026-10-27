

# Curriculum Vitae

**Alakhe Mxakato**
(+27) 79 580 6191 | sbumabudah824@gmail.com | [LinkedIn](https://www.linkedin.com/in/alakhe-mxakato-767825352/) | [GitHub](https://github.com/AlakheMxakato)
## EDUCATION
* Good Hope Adventist High School | Cape Town, Western Cape 2018 - 2022
  
* NorthLink College | Cape Town, Western Cape 2023 <br />
  International CompTIA and ICDL Qualification

* Cape Peninsula University of Cape Town | Cape Town, Western Cape 2024 - Present <br />
  Diploma in ICT Application Development
  
## WORK EXPERIENCE
**Tembani Distributors| Jan. 2023** <br />
IT Technician <br />
* Assembled, configured and deployed custom desktop systems including hardware installation, OS setup and 
driver configuration for the company. <br />
* Installed and configured wireless routers and access points and I performed connectivity and performance 
testing. <br />

## PROJECTS
**Study Group System | Oct. 2024**
* I partnered with a team of 5 and developed a fully functional app using Java and real-time database retrieval 
using MySQL. <br />

**Consulting Management System | Aug. 2025**
* Created a high-fidelity wireframe for a consulting management firm which provided a realistic, interactive and 
polished simulation of the final product. <br />

**Student Enrolment System | Nov. 2025**
* I partnered with a group of 3 to create an enrolment app using Java and SQL to create the database that 
stores student and administrator logins and enrolment information.
## TECHNICAL SKILLS
* **Languages:** Html, CSS, JavaScript, Java
* **Software and Tools:** Figma, IntelliJ Idea, Git, GitHub, Apache NetBeans
* **Development Practices:** Agile Methodology Scrum
* **Platforms:** Windows
## REFERENCES
Tembani Distributors – 076 476 4769

## REFLECTION - CODING IN MARKDOWN
**Situation:** I needed to create my first professional CV and was required to use Markdown instead word. <br />
**Task:** My objective was to design a clear and professional CV using Markdown syntax. <br />
**Action:** I learned about Markdown and used it to design my curriculam vitae. <br />
**Result:** I made a clean, professional CV and improved my Markdown documentation skills. <br />

# MOCK INTERVIEW VIDEO

<video src="./MockInterview.mp4" controls width="600"></video>

## REFLECTION - MOCK INTERVIEW
**Situation:** I was required to do a mock interview video to practice answering common interview questions. <br />
**Task:** My goal was to present myself professionally and communicate my skills clearly on camera. <br />
**Action:** I prepared answers using the STAR method, recorded the video, and reviewed my body language and tone. <br />
**Result:** I improved my confidence, communication skills, and readiness for real interviews. <br />

## REFLECTION - GITHUB PAGES
**Situation:** I created my first GitHub Pages site to showcase my projects and Curriculam Vitae. <br />
**Task:** My goal was to set up a simple, professional website using GitHub Pages. <br />
**Action:** I created a repository, added Markdown/HTML content, and configured GitHub Pages settings. <br />
**Result:** I successfully published a live portfolio site and improved my web hosting and GitHub skills. <br />

# SPS Fruit & Vegetable Coolers: Agile Team Charter


## 1. Team Purpose

SPS Fruit & Vegetable Coolers provides secure, refrigerated overnight storage and transport assistance for street vendors in the Cape Town CBD. Our purpose is to reduce produce spoilage, physical strain and stress for vendors who have no safe storage option.

**Team mission:** To validate and deliver a simple, affordable cold storage service that protects vendor income.

**Current goal:** Validate demand through the MVP flyer campaign. Success is defined as 15 to 20 of 50 vendors approached signing up with their contact details.

---

## 2. Team Members and Roles

| Member | Student Number | Role | Responsibilities |
| --- | --- | --- | --- |
| Sesona Ntshatsha | 240773365 | Team Leader and Designer | Facilitates meetings, keeps the backlog prioritised, removes blockers and leads design of flyers and branding. |
| Alakhe Sbusiso Mxakato | 230485316 | Researcher and Presenter | Gathers vendor feedback, validates assumptions with data and leads presentations. |
| Noxolo Portia Ngubo | 221066748 | Writer, Editor and Presenter | Produces and quality-checks written work and supports presentations. |

All members share accountability for the final product. Roles guide responsibility but do not limit contribution.

---

## 3. Core Values

- **Respect:** We listen to every opinion and value each member's contribution.
- **Accountability:** We do what we commit to and communicate early if we cannot.
- **Transparency:** We share progress, problems and mistakes openly.
- **Customer focus:** Every decision is tested against the needs of the street vendor.
- **Continuous improvement:** We reflect regularly and adapt how we work.

---

## 4. Working Agreements

### Ways of working

- We work in one-week sprints with a shared product backlog and a visible task board (To Do, In Progress, Done).
- A short stand-up is held three times a week, either in person or on WhatsApp. Each member states what was done, what is planned and any blockers.
- Sprint planning takes place at the start of each sprint, and a sprint review and retrospective at the end.

### Communication

- The team WhatsApp group is the main channel for daily communication, and messages are answered within 24 hours.
- Shared documents are stored in one common cloud folder with clear version names.

### Decision making

- Decisions are made by consensus. If consensus cannot be reached, the team votes and the majority decision stands.
- Customer feedback from vendors takes priority over personal preference.

### Definition of Done

- A task is complete only when it has been reviewed by at least one other member, meets the assignment or business requirement, and is uploaded to the shared folder.

### Conflict resolution

1. Issues are raised directly and respectfully with the person concerned first.
2. If unresolved, the issue is discussed with the whole team at the next meeting.
3. If it remains unresolved, the matter is referred to the lecturer for guidance.

---

## 5. Boundaries and Constraints

- Work stays within the agreed target market: Cape Town CBD fruit and vegetable vendors without their own vehicle.
- Spending must stay within the estimated startup budget of R70,500, and no commitments are made without team approval.
- All work must be original, properly referenced and in line with university academic integrity rules.
- Vendor information collected during research is kept confidential and used only for the project.
- Members may not take on work that exceeds their capacity without informing the team.

---

## 6. Risks and Team Response

| Risk | Team Response |
| --- | --- |
| **Market risk:** Vendors may not switch. | Test demand early with the MVP. |
| **Operational risk:** Delays or equipment failure may reduce trust. | Plan ahead and keep backup options. |
| **Team risk:** Missed deadlines or unequal workload. | Raise concerns early and review workload at each retrospective. |

---
# User Stories and Tasks

**Format:** As a [user], I want [feature], so that [benefit].

---

| # | User story | Acceptance criteria | Tasks | Priority |
| --- | --- | --- | --- | --- |
| 1 | As a new vendor, I want to create an account with my name, trading spot, username, phone and 4-digit PIN, so that I can start using cold storage. | All fields are required.<br>The PIN is exactly 4 digits.<br>Duplicate usernames are rejected. | Build the sign-up form.<br>Add validation.<br>Save to the `profiles` table. | Must |
| 2 | As a vendor, I want to log in with my username and PIN, so that I can see my storage. | Correct details open my dashboard.<br>Wrong details show an error. | Build the login form.<br>Check credentials.<br>Handle errors. | Must |
| 3 | As a vendor, I want to see how many crates I have stored and in which unit, so that I always know what is in the cooler. | The home card shows the crate count, unit number and start date. | Design the storage card.<br>Query the active booking. | Must |
| 4 | As a vendor, I want to see the hub closing time, so that I drop off my crates before 18:00. | A highlighted notice shows the closing time on the dashboard. | Add a closing time to the hub data.<br>Build the banner. | Should |
| 5 | As a vendor, I want to access a QR code linked to my storage booking, so that the facility manager can identify my booking and direct me to my assigned storage unit. | A unique QR code is generated for each confirmed storage booking.<br>When the facility manager scans it, the system displays the booking details and assigned storage unit. | Generate a unique QR code linked to the booking.<br>Display the QR code on the vendor's dashboard.<br>Enable the facility manager to scan the QR code and retrieve the booking details. | Must |
| 6 | As a vendor, I want to modify my storage booking, so that I only pay for the space I need. | I can change my crate count and confirm the change. | Build the modify form.<br>Update the booking. | Should |
| 7 | As a vendor, I want to book transport assistance (a facility Bakkie), so that I can collect my stock from the supplier. | I can pick a date, time and location and get a confirmation. | Build the request form.<br>Save the request.<br>Show its status. | Should |
| 8 | As a vendor, I want to choose to pay for my storage fortnightly or monthly, so that I can match my payments to when I earn money. | I can select fortnightly or monthly when booking and change it later.<br>The amount due and the next due date are shown before I confirm. | Add a payment frequency option to the booking form.<br>Calculate the amount and next due date.<br>Save the choice to the booking. | Should |

---

## Screenshots

| | | |
| --- | --- | --- |
| ![Landing screen with Vendor, Facility Manager and System Admin options](https://github.com/AlakheMxakato/AlakheMxakato.github.io/blob/main/LandingPage.png?raw=true) |
| ![Vendor sign-up form](https://github.com/AlakheMxakato/AlakheMxakato.github.io/blob/main/Vendor%20SignUp.png?raw=true) | ![Vendor login form](https://github.com/AlakheMxakato/AlakheMxakato.github.io/blob/main/LogIn.png?raw=true) |
| ![Vendor dashboard showing active storage, closing time banner and QR code button](https://github.com/AlakheMxakato/AlakheMxakato.github.io/blob/main/VendorStorage.png?raw=true) | ![Vendor account page](https://github.com/AlakheMxakato/AlakheMxakato.github.io/blob/main/VendorAccount.png?raw=true) | ![Storage package screen with billing cycle and payment method](https://github.com/AlakheMxakato/AlakheMxakato.github.io/blob/main/BillingCycle.png?raw=true) |

---

## REFLECTION

**Situation:** SPS Coolers is a smart cold storage app that helps street vendors manage their bookings and access the facility.

**Task:** Our team developed user stories and broke them into manageable tasks for planning and development.

**Action:** We wrote vendor-focused user stories with acceptance criteria, prioritised them using MoSCoW and split them into tasks.

**Result:** We now have a clear Product Backlog and Sprint 1 backlog, and we learned to define priorities and acceptance criteria before development begins.

# Product and Sprint Backlog

---

## Product Backlog


| Rank | ID | Backlog item | Priority | Points | Sprint | Status |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | PB-01 | As a new vendor, I want to create an account with my name, trading spot, username, phone and 4-digit PIN, so that I can start using cold storage. | Must | 3 | 4 | Done |
| 2 | PB-02 | As a vendor, I want to log in with my username and PIN, so that I can see my storage. | Must | 2 | 4 | Done |
| 3 | PB-03 | As a vendor, I want to see how many crates I have stored and in which unit, so that I always know what is in the cooler. | Must | 3 | 5 | Done |
| 4 | PB-04 | As a vendor, I want to access a QR code linked to my booking, so that the facility manager can identify my booking and direct me to my storage unit. | Must | 5 | 6 | Done |
| 5 | PB-05 | Test all stories against their acceptance criteria and fix bugs. | Must | 5 | 9 | Done |
| 6 | PB-06 | As a vendor, I want to see the hub closing time, so that I drop off my crates before 18:00. | Should | 2 | 5 | Done |
| 7 | PB-07 | As a vendor, I want to modify my storage booking, so that I only pay for the space I need. | Should | 3 | 7 | Done |
| 8 | PB-08 | As a vendor, I want to book transport assistance (a facility Bakkie), so that I can collect my stock from the supplier. | Should | 5 | 7 | Done |
| 9 | PB-09 | As a vendor, I want to choose fortnightly or monthly payments, so that I can match my payments to when I earn money. | Should | 3 | 8 | Done |
| 10 | PB-10 | As a vendor, I want to select a payment method and view my payment history, so that I can pay easily and track my invoices. | Should | 3 | 8 | Done |
| 11 | PB-11 | As an administrator, I want an admin view, so that I can oversee hub operations. | Could | 3 | 8 | Done |
| 12 | PB-12 | Integrate a real payment gateway. | Won't (this release) | 8 | None | Not started |
| 13 | PB-13 | Add push notifications for booking and closing time reminders. | Won't (this release) | 5 | None | Not started |

**Velocity:** Sprint 4 (5 points), Sprint 5 (5), Sprint 6 (5), Sprint 7 (8), Sprint 8 (9) and Sprint 9 (5), giving 37 points completed in total.

### Product Backlog Reflection

**Situation:** Our team needed a clear list of everything required to build the SPS Coolers app.

**Task:** We created and prioritised a product backlog from our user stories.

**Action:** We ranked items using MoSCoW, estimated story points and refined the list at each sprint retrospective.

**Result:** We delivered 37 points of work and learned that early prioritisation keeps the team focused on what vendors need most.

---

## Sprint Backlogs


**Definition of Done (all sprints):** The task is reviewed by another member, meets the acceptance criteria and is pushed to the shared repository.

| Sprint | Dates | Sprint goal | Items | Points | Planned hours |
| --- | --- | --- | --- | --- | --- |
| 4 | 18 to 21 August | Vendors can create an account and log in securely. | PB-01, PB-02 | 5 | 22 |
| 5 | 25 to 28 August | Vendors can see their active storage and the closing time. | PB-03, PB-06 | 5 | 15 |
| 6 | 1 to 4 September | Each booking has a QR code the facility manager can scan. | PB-04 | 5 | 16 |
| 7 | 8 to 11 September | Vendors can modify their booking and request transport. | PB-07, PB-08 | 8 | 20 |
| 8 | 15 to 18 September | Vendors can choose how and when to pay, and admins have an overview. | PB-09, PB-10, PB-11 | 9 | 25 |
| 9 | 22 to 25 September | The app is fully tested, fixed and published. | PB-05 | 5 | 21 |

---

### Sprint 4 (18 to 21 August 2026)

**Sprint goal:** Vendors can create an account and log in securely using a username and 4-digit PIN.

| Task | Item | Owner | Hours | Status |
| --- | --- | --- | --- | --- |
| Build the sign-up form | PB-01 | Sesona | 4 | Done |
| Add validation for required fields and the 4-digit PIN | PB-01 | Alakhe | 3 | Done |
| Reject duplicate usernames | PB-01 | Alakhe | 2 | Done |
| Save new vendors to the `profiles` table | PB-01 | Sesona | 2 | Done |
| Build the login form | PB-02 | Sesona | 3 | Done |
| Check credentials against stored details | PB-02 | Alakhe | 2 | Done |
| Handle errors and write clear error messages | PB-02 | Noxolo | 2 | Done |
| Test both items against acceptance criteria and complete peer review | PB-01, PB-02 | Noxolo | 3 | Done |
| Update the Trello board and logbook | All | Noxolo | 1 | Done |

**Review and retrospective:** Both items were completed. Duplicate username errors were not visible at first, so we agreed to test error messages earlier in future sprints.

---

### Sprint 5 (25 to 28 August 2026)

**Sprint goal:** Vendors can see their active storage and the hub closing time on the dashboard.

| Task | Item | Owner | Hours | Status |
| --- | --- | --- | --- | --- |
| Design the storage card | PB-03 | Sesona | 3 | Done |
| Query the active booking only | PB-03 | Alakhe | 3 | Done |
| Display crate count, unit number and start date | PB-03 | Sesona | 2 | Done |
| Add the closing time to the hub data | PB-06 | Alakhe | 1 | Done |
| Build the highlighted 18:00 closing time banner | PB-06 | Sesona | 2 | Done |
| Test both items against acceptance criteria and complete peer review | PB-03, PB-06 | Noxolo | 3 | Done |
| Update the Trello board and logbook | All | Noxolo | 1 | Done |

**Review and retrospective:** The dashboard first showed outdated bookings. We changed the query to return the active booking only. In future we will test with more than one booking per vendor.

---

### Sprint 6 (1 to 4 September 2026)

**Sprint goal:** Each confirmed booking has a unique QR code that the facility manager can scan to see the booking and assigned unit.

| Task | Item | Owner | Hours | Status |
| --- | --- | --- | --- | --- |
| Generate a unique QR code linked to each booking | PB-04 | Alakhe | 4 | Done |
| Display the QR code on the vendor dashboard | PB-04 | Sesona | 3 | Done |
| Build the facility manager scan screen showing booking details and unit | PB-04 | Alakhe | 4 | Done |
| Increase QR code size and contrast after small screen tests | PB-04 | Sesona | 1 | Done |
| Test scanning on different phones and complete peer review | PB-04 | Noxolo | 3 | Done |
| Update the Trello board and logbook | All | Noxolo | 1 | Done |

**Review and retrospective:** Some QR codes were hard to scan on small screens, which we fixed by increasing size and contrast. We will test on a wider range of devices earlier.

---

### Sprint 7 (8 to 11 September 2026)

**Sprint goal:** Vendors can change their crate count and request transport assistance for stock collection.

| Task | Item | Owner | Hours | Status |
| --- | --- | --- | --- | --- |
| Build the modify booking form | PB-07 | Sesona | 3 | Done |
| Update the booking with the new crate count and confirm | PB-07 | Alakhe | 3 | Done |
| Build the transport request form with date, time and location | PB-08 | Sesona | 4 | Done |
| Save the request and show its status | PB-08 | Alakhe | 4 | Done |
| Write confirmation messages for both features | PB-07, PB-08 | Noxolo | 2 | Done |
| Test both items using shared test accounts and complete peer review | PB-07, PB-08 | Noxolo | 3 | Done |
| Update the Trello board and logbook | All | Noxolo | 1 | Done |

**Review and retrospective:** Testing was slow at first. Sharing test accounts so that each member tested a different feature solved this, and we will keep this practice.

---

### Sprint 8 (15 to 18 September 2026)

**Sprint goal:** Vendors can choose how and when to pay, and administrators have an overview of hub operations.

| Task | Item | Owner | Hours | Status |
| --- | --- | --- | --- | --- |
| Add the fortnightly or monthly option to the booking form | PB-09 | Sesona | 3 | Done |
| Calculate the amount due (R50 per crate fortnightly, R90 per crate monthly) and the next due date | PB-09 | Alakhe | 4 | Done |
| Save the billing choice to the booking | PB-09 | Alakhe | 2 | Done |
| Build the payment method selection (Capitec Pay, Instant EFT, card) | PB-10 | Sesona | 3 | Done |
| Build the payment history screen | PB-10 | Sesona | 3 | Done |
| Build the admin view | PB-11 | Alakhe | 4 | Done |
| Document that payments are simulated for the prototype | PB-10 | Noxolo | 2 | Done |
| Test all three items against acceptance criteria and complete peer review | PB-09, PB-10, PB-11 | Noxolo | 3 | Done |
| Update the Trello board and logbook | All | Noxolo | 1 | Done |

**Review and retrospective:** This was our largest sprint at 9 points. A real payment gateway was outside the project scope, so we simulated payments and stated this clearly in our documentation.

---

### Sprint 9 (22 to 25 September 2026)

**Sprint goal:** The app is fully tested against all acceptance criteria, free of known bugs and published.

| Task | Item | Owner | Hours | Status |
| --- | --- | --- | --- | --- |
| Test every user story against its acceptance criteria | PB-05 | Noxolo | 5 | Done |
| Fix the final bugs found during testing | PB-05 | Alakhe | 4 | Done |
| Check final screens for design and brand consistency | PB-05 | Sesona | 3 | Done |
| Publish the final version of the app | PB-05 | Alakhe | 2 | Done |
| Prepare the final presentation | PB-05 | Alakhe | 3 | Done |
| Compile the documentation for submission | PB-05 | Noxolo | 3 | Done |
| Update the Trello board and logbook | All | Noxolo | 1 | Done |

**Review and retrospective:** Heritage Day on 24 September reduced available time, so we worked on 22, 23 and 25 September. The app was completed and published on 25 September 2026 with all committed items done.

---

### Sprint Backlog Reflection

**Situation:** Our team needed to turn the product backlog into manageable weekly work.

**Task:** We planned each sprint with a clear goal, tasks, owners and time estimates.

**Action:** We tracked tasks on Trello, checked work against our Definition of Done and held a retrospective after every sprint.

**Result:** We completed every sprint goal and finished the app on 25 September, and learned that small tasks and regular reviews reduce delays.

# Agile Logbook

 28 July 2026 to 25 September 2026

**Final product:** SPS Coolers mobile app, completed on 25 September 2026. [View the live app](https://sps-coolers-mobile-a-62e8.bolt.host/)

---

## Walkthrough

| Question | Response |
| --- | --- |
| What do we need to do to advance this piece of work? | Hold regular stand-ups, follow the sprint backlog and review every task before it is marked as done, as agreed in our team charter. |
| Is anyone working on anything that is not on the board? | No, everyone worked only on tasks from the Trello board and the product backlog. |
| What did we need to finish as a team? | A working mobile app that lets street vendors book and manage cold storage, with all Must and Should user stories completed. |
| Were there any bottlenecks or blockers to the flow of work? | Time management and testing delays at times, which we resolved by splitting tasks and testing earlier. |

---

## Logbook

Each week was one sprint. Stand-ups were held three times a week in person or on WhatsApp, and every sprint ended with a short review and retrospective.

| Sprint and dates | What did we complete since the last stand-up? | What do we plan to complete next? | Impediments, risks or problems |
| --- | --- | --- | --- |
| **Sprint 1**<br>28 to 31 July | We completed the wireframes, opened the GitHub repository, coded and debugged the front end and uploaded it to GitHub Pages. | Present the front end and get approval from our lecturer. | The web application did not work after upload because the file was not visible to the command prompt. We corrected the file path and linked it again. |
| **Sprint 2**<br>4 to 7 August | We completed the front end, finished the brand guide presentation and updated the Trello board. | Start the solution architecture. | Keeping the presentation in one theme. Sesona reviewed all slides for consistency. |
| **Sprint 3**<br>11 to 14 August | We completed the solution architecture and database design, and moved the user stories into a prioritised product backlog using MoSCoW. We decided to build a mobile app because vendors mainly use phones. | Build the sign-up and login features. | Choosing a development approach with limited time. We agreed to use Bolt to build faster and focus on testing. |
| **Sprint 4**<br>18 to 21 August | We completed vendor sign-up and login with a 4-digit PIN, required fields and rejection of duplicate usernames (Must stories). | Build the vendor dashboard with the storage card and closing time notice. | Duplicate usernames were not showing an error message. We added validation and retested. |
| **Sprint 5**<br>25 to 28 August | We completed the dashboard showing crate count, unit number, start date and the 18:00 closing time banner. | Build the QR code feature for bookings. | The dashboard showed outdated bookings. We changed the query to return only the active booking. |
| **Sprint 6**<br>1 to 4 September | We completed the unique QR code for each confirmed booking and the facility manager scan screen that displays booking details and the assigned unit. | Build the modify storage and transport assistance features. | Some QR codes were hard to scan on small screens. We increased the code size and contrast. |
| **Sprint 7**<br>8 to 11 September | We completed the modify booking feature and the Bakkie transport request with date, time, location and status. | Build the payment options and account page. | Slow progress on testing. We shared test accounts so each member tested a different feature. |
| **Sprint 8**<br>15 to 18 September | We completed the choice of fortnightly (R50 per crate) or monthly (R90 per crate) billing, payment method selection, payment history, the account page and the facility manager and admin views. | Carry out full testing and fix remaining bugs. | Payments are simulated because a real payment gateway was outside the project scope. We stated this clearly in our documentation. |
| **Sprint 9**<br>22 to 25 September | We completed full testing of all user stories against their acceptance criteria, fixed final bugs and published the finished app on 25 September. | Prepare the final presentation and submission. | Heritage Day on 24 September reduced available time, so we worked on 22, 23 and 25 September. No other impediments. |

---

## REFLECTION

**Situation:** Our team needed to turn the SPS Coolers business idea into a working app for street vendors.

**Task:** We planned, built and tested the app over nine one-week sprints.

**Action:** We followed our team charter, used a prioritised backlog and reviewed each task before marking it done.

**Result:** We completed the app on 25 September, and learned that early testing and clear acceptance criteria reduce delays.
