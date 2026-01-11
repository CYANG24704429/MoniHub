# MoniHub

## Empowering PNG Youth Through Financial Literacy

MoniHub is a financial literacy education hub designed to bridge the gap between traditional cultural financial practices and the modern digital economy. Built specifically for youth in Papua New Guinea, MoniHub transforms financial education into an engaging, culturally-relevant, and aspirational experience—empowering the next generation to build sustainable financial futures.

---

## Features

### **Interactive Learning Modules**

Gamified lessons that make financial education engaging and accessible to PNG youth.

- **Budgeting Essentials**: Learn practical money management strategies adapted to the PNG context, including navigating family expectations and community obligations
- **Saving Strategies**: Master effective saving techniques that align with both personal goals and cultural values (e.g., managing *Wantok* expectations while protecting personal savings)
- **Debt Management**: Understand borrowing responsibly and strategies for managing debt in a culturally-aware framework
- **Gamified Progress**: Earn badges, unlock achievement levels, and compete with peers to stay motivated
- **Contextual Scenarios**: Real-world situations reflecting PNG life—managing school fees, starting a business, handling unexpected expenses—all while respecting community ties

---

### **The "Stori" Vault**

A community-driven content library celebrating PNG financial wisdom and success.

- **Bite-Sized Financial Stories**: Short, narrative-driven advice pieces that are easy to consume and remember
- **Local Role Models**: Success stories from PNG entrepreneurs, educators, and financial achievers
- **Cultural Respect**: Content that honors traditional practices while introducing modern financial tools
- **Diverse Topics**: From growing a small business to negotiating family finances to investing in education
- **Inspirational Content**: Real people, real journeys—showing what's possible in your own community

---

### **Goal Setting & Progress Visualization**

Turn financial dreams into achievable milestones.

- **Savings Targets**: Set personalized goals like "School Fees Fund," "Business Startup Capital," or "Emergency Reserve"
- **Visual Progress Tracking**: Watch your goal grow with animated progress bars and milestone celebrations
- **Customizable Timelines**: Create short-term (3 months) and long-term (1+ year) goals that match your life plans
- **Accountability Dashboard**: A personal hub to monitor progress and stay motivated
- **Milestone Rewards**: Celebrate wins when you reach 25%, 50%, 75%, and 100% of your savings goals

---

## Our Mission

MoniHub exists to democratize financial education for PNG youth. We believe that financial literacy is not a luxury—it's a foundation for personal empowerment and community development. By blending cultural respect with modern financial tools, MoniHub helps young Papua New Guineans make confident, informed decisions about money while honoring the values that matter most to them.

---

## Get Started

Ready to take control of your financial future? Join MoniHub today and start your journey toward financial empowerment.

---

# Business-Overview.md
markdown

MoniHub
Empowering PNG Youth Through Financial Literacy

MoniHub is a simple, mobile-friendly financial literacy web app designed for young people in Papua New Guinea. It teaches budgeting, saving, mobile money basics, and scam awareness through short lessons, quizzes, and practical tools like a budget planner and savings tracker.

This project was created for the BRIDGES Summer School Hackathon by Team Gitty Up.

---

Problem We Are Solving

Many young people in PNG lack access to practical financial education. This leads to:

- Poor budgeting habits  
- Difficulty saving  
- Limited understanding of mobile banking  
- High vulnerability to scams  
- No youth-friendly tools to plan money  

MoniHub provides simple, localized learning that youth can access instantly through QR codes.

---

Key Features

- Learning Modules – Short lessons on budgeting, saving, and avoiding scams  
- Quizzes – Reinforce learning with simple questions  
- Budget Planner – Helps youth calculate income vs expenses  
- Savings Goals – Track progress toward personal goals  
- QR Code Access – Fast, secure, error-free onboarding  
- Local Storage – Saves progress on the device  

---

Business Analysis Documentation

All Business Analyst documentation is stored in the /docs folder:

- Business Overview  
- Requirements  
- User Personas  
- User Journey  

These documents define the problem, users, requirements, and flow of the MoniHub solution.

---

Tech Stack

- HTML  
- CSS  
- JavaScript  
- LocalStorage (for sanprogress)  
- GitHub Pages (for hosting)

No backend required.

---

Deployment

This project can be deployed using GitHub Pages:

1. Go to Settings  
2. Select Pages  
3. Choose:  
   - Branch: main  
   - Folder: / (root)  
4. Save  

GitHub will generate a live URL that can be turned into a QR code.

---

Team Gitty Up

- Developers: Team Members  
- Designer: Team Members  
- Project Lead: Team Members
- Business Analyst: Charlotte

---

License

This project is open-source and free to use for educational purposes.
`

---

2. docs/business-overview.md

`markdown

MoniHub – Business Overview

1. Problem Statement

Many young people in Papua New Guinea lack access to practical, easy-to-understand financial education. Most learning happens informally, and schools rarely teach budgeting, saving, mobile banking, or how to avoid scams. As a result, youth often struggle with:

- Managing their first income  
- Distinguishing needs from wants  
- Setting savings goals  
- Understanding bank and mobile money products  
- Protecting themselves from digital fraud  

MoniHub aims to close this gap by providing simple, mobile-friendly financial literacy tools designed specifically for PNG youth.

---

2. Target Users and Clients

Primary Users
- Youth aged 15–30 in PNG  
- Students, first-time earners, informal workers, and young entrepreneurs  

Secondary Users
- Teachers, youth mentors, community leaders  
- Parents who want to guide their children  

Clients / Stakeholders
- Schools and training institutions  
- NGOs and youth empowerment programs  
- Financial institutions promoting financial inclusion  
- Government agencies supporting youth development and digital literacy  

---

3. Product Description

MoniHub is a digital financial literacy companion that delivers:

- Short, localized learning modules  
- A simple budget planner  
- A savings goal tracker  
- Gamified quizzes and badges  
- QR-code access for fast onboarding  
- Mobile-first design for low-data environments  

---

4. Key Problems MoniHub Solves

- Lack of structured financial education  
- Limited access to trustworthy financial information  
- Poor budgeting and saving habits  
- High vulnerability to scams  
- No youth-friendly tools to plan and track money  

---

5. High-Level Value Proposition

For Youth
- Practical, PNG-relevant lessons  
- Easy to access on basic smartphones  
- Engaging through challenges and progress tracking  

For Schools, NGOs, and Partners
- Ready-made financial literacy toolkit  
- Easy distribution through QR codes  
- Scalable to thousands of youth  

---

6. Strategic Impact

MoniHub supports long-term national goals by:

- Improving financial inclusion  
- Strengthening youth economic participation  
- Reducing vulnerability to fraud  
- Encouraging responsible money habits early in life  
`

---

3. docs/requirements.md

`markdown

MoniHub – Initial Requirements

1. Functional Requirements

Access & Onboarding
- FR1: Users can access MoniHub by scanning a QR code.  
- FR2: The landing page loads quickly on low-data connections.  
- FR3: Users can create a simple profile (name, age range, province).  

Learning Modules
- FR4: Users can view a list of financial literacy modules.  
- FR5: Users can open a module and read short lessons.  
- FR6: Users can complete quizzes at the end of each module.  
- FR7: The system tracks completed modules.  

Tools & Features
- FR8: Users can use a simple budget planner.  
- FR9: Users can set savings goals and track progress.  
- FR10: Users can earn badges for completing modules.  

QR Code Integration
- FR11: Each QR code can link to a specific module or feature.  
- FR12: QR codes can be printed or shared digitally.  

Admin / Partner Features (Future)
- FR13: Partners can generate QR codes.  
- FR14: Partners can view engagement analytics.  

---

2. Non-Functional Requirements

- NFR1: Mobile-first design  
- NFR2: Low data usage  
- NFR3: Simple English and PNG-friendly examples  
- NFR4: Secure handling of user data  
- NFR5: Works on basic Android devices  
- NFR6: Content easy to update  

---

3. Assumptions

- Most users have access to a smartphone.  
- Users are familiar with QR codes.  
- Partners can print or distribute QR codes.  
- Internet access may be unstable.  

---

4. Constraints

- Limited development time  
- Must be simple for low digital literacy  
- Must work in low-bandwidth environments  
`

---

4. docs/user-personas.md

`markdown

MoniHub – User Personas

Persona 1: Lewa (17, Student – Lae)

Background
- Grade 11 student  
- Has a basic Android phone  
- Receives small pocket money  

Goals
- Learn to save  
- Understand budgeting  
- Avoid scams  

Pain Points
- No financial education  
- Easily influenced by peers  
- Confused by mobile banking fees  

How MoniHub Helps
- Simple budgeting lessons  
- Savings goal tracker  
- Scam awareness module  

---

Persona 2: Kela (22, Informal Worker – Port Moresby)

Background
- Sells betelnut and drinks  
- Income changes daily  
- Wants to save for a table and umbrella  

Goals
- Track income  
- Save consistently  
- Understand bank accounts  

Pain Points
- Irregular income  
- Distrust of banks  
- No planning tools  

How MoniHub Helps
- Budget planner  
- Savings tracker  
- Clear explanations of mobile money  

---

Persona 3: Meri (28, Youth Mentor – Goroka)

Background
- Works with church youth  
- Wants structured teaching materials  

Goals
- Teach financial responsibility  
- Use low-data tools  
- Track youth engagement  

Pain Points
- No ready-made materials  
- Youth lose interest quickly  
- Limited digital resources  

How MoniHub Helps
- QR code access  
- Short, engaging modules  
- Printable posters  
`

---

5. docs/user-journey.md

`markdown

MoniHub – User Journey

Stage 1: Awareness
User sees a QR code on a poster, school noticeboard, church hall, or WhatsApp.

Action: Scans QR code  
System: Opens MoniHub instantly  

---

Stage 2: Onboarding
User taps “Start Learning”.

System: Shows simple profile setup  

---

Stage 3: Explore Modules
User sees modules like:

- Budgeting Basics  
- Savings Goals  
- Mobile Money  
- Avoiding Scams  

---

Stage 4: Learn & Interact
User reads a lesson and completes a quiz.

System: Awards a badge and marks module as completed  

---

Stage 5: Apply Tools
User opens:

- Budget Planner  
- Savings Tracker  

System: Saves progress in local storage  

---

Stage 6: Return & Continue
User scans another QR code or reopens the app.

System: Shows progress dashboard  

---

Stage 7: Completion & Impact
User gains financial confidence and applies lessons in real life.

Impact:  
- Better budgeting  
- Improved saving habits  
- Reduced vulnerability to scams  
`


*Built with ❤️ for PNG youth. Let's grow together.*
