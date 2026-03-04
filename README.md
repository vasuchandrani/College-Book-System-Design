# 📚 CollegeBook Database

**CollegeBook Database** is the structured **database design** of the **[CollegeBook](https://github.com/vasuchandrani/College-Book)**- ***Build Your College Story***.  

Thiys project contains the schemas, relations, and queries that power the CollegeBook App, **CollegeBook** is a unique, minimal, and purpose-driven social media platform designed exclusively for college students. Unlike conventional social platforms, CollegeBook is **time-bound**—your account lasts only through your academic course duration. Once you graduate, your account is deleted and a personalized archive file (PDF/HTML) of all your activity is delivered to you as a digital **Memory Book**.

---

##  Vision

To design and maintain a **robust, scalable, and normalized database** that supports all the features of **CollegeBook**, enabling students to collaborate, share, and grow in a distraction-free digital ecosystem.  

---

##  Database Scope

The database supports the complete set of **CollegeBook features**, including:  

###  Campus Feed
- Store and retrieve posts from all students in a college.
- No follower/friend relations — **open visibility by design**.

###  Explore Peers
- Cross-college post exploration via controlled queries.
- Focused on reducing unnecessary connections while keeping visibility intact.

###  Post Features
- Manage likes, saved posts, and shareable external links.
- Like counts stored efficiently (no user name tracking to reduce overhead).  

###  Collab Hub
- Database design for hackathon/project teams:
  - Open team listings
  - Join requests (with status: `Accepted`, `Rejected`, `Need Improvement`)
  - Structured feedback mechanism
- Auto-creation of **team groups** (private chats) only after acceptance.

###  Profile & Achievements
- Centralized user profile schema with:
  - Education details
  - Saved posts
  - Team participation history
- **myCon Tags (Skill Badges)**:
  - Stored with verification data (e.g., contest links, project proof).  

###  Graduation & Digital Memory Book
- Automatic account expiry based on course duration.
- Export functionality to generate **PDF/HTML memory book** from stored data.

---

##  Database Design Highlights
- **ER Diagram** covering Users, Posts, Colleges, Teams, Requests, Chats, and myCons.
- **Relational Schema** with normalized relations to avoid redundancy.
- Support for **referential integrity** with foreign keys.
- Indexes for fast retrieval of posts, profiles, and team listings.

---

##  Why This Database is Different
- Focuses on **purpose-driven relations** (teams, projects, achievements).
- Time-bound accounts for natural cleanup and sentimental closure.
- Inclusive design for introverts and underserved students.

---

## 🛠️ Current Status

🚧 The project is actively in development, expanding with new academic-focused and student-centric features.

---

### 🙌 Made with passion for students, by a student.

**“Code. Create. Empower.”**
