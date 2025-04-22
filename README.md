# 🎵 Mellove – A Music Collaboration Platform for Rising Talents

## 🚨 1. Problem Statement / Need

Despite millions of talented singers across the globe, most remain undiscovered due to a lack of musical networks or platforms designed for real-time music collaboration.

Current platforms often:

- ❌ Do not allow real-time collaboration.
- ❌ Lack competitions and community support.
- ❌ Rely heavily on AI filters and paid access, limiting organic musical growth.

---

## 💡 2. What is Mellove?

**Mellove** is a full-stack music collaboration web platform that aims to:

- Foster **collaboration and creativity** in a passionate music community.
- Empower **underrated singers** through weekly/monthly competitions.
- Provide a **SingAlong** feature for solo, asynchronous, and real-time duet singing.
- Act as a **social hub** where singers, lyricists, and music lovers unite to create and share.

---

## 🌟 3. Core Features (Level-1 Scope)

### A. Authentication

- Sign up/login with email-password.
- Google OAuth login.
- JWT-based secure session management.

### B. User Dashboard

- View uploaded songs.
- Track competition entries.
- Discover popular singers & collaborators.

### C. Song Upload

- Upload covers or original compositions (audio format).
- Audio securely stored (Cloudinary or equivalent).
- Metadata stored in MongoDB: `title`, `genre`, `language`, `tags`, `duration`, `timestamp`.

### D. Karaoke Studio

- Choose karaoke tracks (YouTube embed / open-source).
- Record voice with karaoke.
- Save/share personal version.

### E. Weekly Competitions

- Submit entries weekly.
- Users vote on performances.
- Admin selects winners based on votes + criteria.
- Entries/voting managed in DB.

### F. Music Discovery

- Feed showing trending songs.
- Filter by tags (genre, mood, language).
- Like & comment features.

---

## 🔮 4. Future Expansion (Beyond Level-1)

### 🎤 Real-Time Live Collab

- WebRTC + Socket.IO based duets.
- UI inspired by Zoom + JamStudio.

### 🎶 Async Duets (SingAlong)

- User 1 records → User 2 overlays voice later.
- Final duet is merged and published.

### 🏆 Live Recording Studio

- Multi-track voice layering.
- Basic effects: reverb, pitch, volume.
- Save professional-level recordings.

---

## 🛠 5. Technical Stack

| Layer               | Technology                        |
| ------------------- | --------------------------------- |
| **Frontend**        | React.js, Tailwind CSS            |
| **Backend**         | Node.js, Express.js               |
| **Database**        | MongoDB, Mongoose                 |
| **Auth**            | JWT, bcrypt, Google OAuth v2      |
| **File Upload**     | Multer, Cloudinary (or free alt.) |
| **Deployment**      | Vercel (Frontend), Render/Cyclic  |
| **Design Tools**    | Figma                             |
| **Version Control** | Git, GitHub Projects              |

---

## 🧩 6. Capstone Level-1 Concept Mapping

| Concept                    | Proof of Work                                           |
| -------------------------- | ------------------------------------------------------- |
| **Low-fid Design**         | Wireframes for dashboard, upload, karaoke pages         |
| **High-fid Design**        | Figma UI with transitions, gradients, responsive design |
| **GitHub Project Setup**   | Project board, Kanban tasks                             |
| **APIs (GET, POST, PUT)**  | CRUD operations for songs, user profiles, competitions  |
| **Backend Deployed**       | Hosted on Render                                        |
| **Database Schema**        | Users, Songs, Competitions - Mongoose schemas           |
| **DB Read/Write Ops**      | Uploading, editing, retrieving songs                    |
| **DB Relationships**       | One-to-many: Users → Songs; Songs → Comments (nested)   |
| **Frontend Init**          | React + Tailwind setup                                  |
| **Frontend Components**    | Navbar, UploadForm, Dashboard, CompetitionCard          |
| **Design Match**           | Frontend aligns with Figma high-fid design              |
| **File Uploads**           | Multer + Cloudinary for audio                           |
| **Authentication**         | JWT-secured auth, protected routes                      |
| **Update/Delete in React** | Edit/delete song feature                                |
| **API Testing**            | Bruno collection for all endpoints                      |
| **JWT in App**             | Token-based route access                                |

---

## 📅 7. Milestone Plan (Level-1 Completion Timeline)

| Week       | Tasks                                | Daily Breakdown                                                                                                                           |
| ---------- | ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Week 1** | Feature finalization, design         | Day 1-2: Brainstorm features, user personas <br> Day 3-4: Wireframes <br> Day 5-6: High-fid Figma design <br> Day 7: Review               |
| **Week 2** | GitHub setup, backend, DB schemas    | Day 1-2: Init Node/Express <br> Day 3-4: Mongoose Models <br> Day 5-6: Backend routes <br> Day 7: Postman/Bruno test                      |
| **Week 3** | Frontend UI, GET/POST integration    | Day 1-2: Init React + Tailwind <br> Day 3-4: Build UI Components <br> Day 5-6: Connect backend <br> Day 7: Data testing                   |
| **Week 4** | Edit/Delete, file upload, deployment | Day 1-2: PUT & DELETE in React <br> Day 3-4: Multer + Cloudinary <br> Day 5: Backend deploy <br> Day 6: Frontend deploy <br> Day 7: Debug |
| **Week 5** | Testing, polish, peer review         | Day 1-2: CRUD testing (Bruno) <br> Day 3-4: Match Figma design <br> Day 5-6: Animations, responsiveness <br> Day 7: Mentor review         |
| **Week 6** | Documentation, demo, submission      | Day 1: Write Capstone doc <br> Day 2: Create demo video <br> Day 3: Final test <br> Day 4: Submit <br> Day 5-7: Rework buffer             |

---

> 🔗 **Mellove is not just a platform—it's a movement to amplify unheard voices and connect creators through the love of music.**

---
