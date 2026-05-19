\# Mistakes Recall — Track \& Review Your Learning Mistakes



\*\*Mistakes Recall\*\* is a completely local, browser‑based tool for students who want to \*\*systematically capture, organize, and review their mistakes\*\*.  

Instead of forgetting that one tricky derivative you got wrong or the physics concept that always trips you up, you log it once and then \*\*recall it regularly\*\* using a built‑in card review mode.



\---



\## ✨ Features



\### 📝 Mistake Logging

\- \*\*Fast Add\*\* (`N` key) – capture a mistake in seconds, even from anywhere in the app.

\- Each mistake records a \*\*title\*\*, \*\*explanation\*\*, \*\*correction\*\*, \*\*formula\*\*, \*\*tags\*\*, and an optional \*\*screenshot\*\*.

\- Mistakes are linked to a \*\*subject\*\* and a \*\*lesson\*\* for perfect organisation.



\### 🗂️ Subjects \& Lessons

\- Create \*\*subjects\*\* (Math, Physics, …) with custom colours and icons.

\- Inside subjects, add \*\*lessons\*\* (e.g., “Derivatives”, “Complex Numbers”).

\- View all mistakes per lesson or per subject at a glance.



\### 📌 Pinning

\- Pin the most important mistakes – they always appear at the top of lists and in review queues.

\- Pinned mistakes get a dedicated sidebar section for instant access.



\### 📦 Recall Groups

\- Bundle specific lessons together into a \*\*Recall Group\*\* (e.g., “BAC Geometry Bundle”).

\- Review all mistakes from a group with one click – perfect for exam prep.



\### 🔁 Card‑based Review Mode

\- Flip through your mistakes like flashcards, showing all details (correction, formula, screenshot).

\- \*\*Shuffle mode\*\* (`S` key) randomises the order (pinned cards stay first).

\- Navigate with `←` `→` keys or on‑screen buttons.

\- Jump to any card in the queue.



\### 🔍 Full‑text Search \& Filters

\- Search across all mistakes, subjects, lessons, and tags.

\- Filter by \*\*subject\*\*, \*\*recall group\*\*, or a combination.

\- Results instantly update as you type.



\### 📊 Dashboard Statistics

\- See at a glance: total mistakes, subjects, lessons, pinned count, and recall groups.

\- Recent mistakes list with subject colour coding.



\### 🌗 Dark \& Light Mode

\- Toggle between a dark theme (default) and a light theme.

\- Customisable \*\*accent colour\*\* (blue, green, orange, etc.).



\### 💾 Data Ownership \& Privacy

\- 100% local – all data is stored in your browser’s `localStorage`.

\- Export a \*\*JSON backup\*\* anytime, import it to restore or move devices.

\- No servers, no accounts, no tracking.



\### ⌨️ Keyboard Shortcuts

| Key | Action |

|-----|--------|

| `N` | Fast‑add a new mistake |

| `←` `→` | Previous / next card (review mode) |

| `S` | Toggle shuffle (review mode) |

| `Esc` | Close modal or exit review |



\### 📱 Responsive \& Mobile‑friendly

\- Works on desktop, tablet, and phone.

\- Sidebar hides automatically on small screens.



\---



\## 🧠 How It Works



The app is a \*\*single HTML file\*\* that runs entirely in your browser.  

It uses vanilla JavaScript (no frameworks) with a simple state‑driven rendering system:



1\. \*\*Data Model\*\* – All data (subjects, lessons, mistakes, recall groups, settings) is kept in a single JavaScript object and saved to `localStorage` after every change.

2\. \*\*Views\*\* – The sidebar and main content are re‑rendered whenever you navigate or modify data.

3\. \*\*Review Mode\*\* – When you start a review, the selected mistakes are placed into a queue. Pinned items are always shown first, and shuffling (if enabled) randomises only the unpinned cards.

4\. \*\*Search\*\* – A simple filter function checks the title, explanation, correction, formula, tags, subject name, and lesson name against your query.



Everything is self‑contained – open the file and start using it.



\---



\## 🚀 Getting Started



\### 1. Open the App

\- Download the `index.html` file.

\- Double‑click to open it in any modern browser (Chrome, Firefox, Edge, Safari).



\### 2. Create a Subject

\- Click \*\*“Add Subject”\*\* in the sidebar.

\- Choose a name (e.g., “Mathematics”), an icon, and a colour.



\### 3. Add a Lesson

\- Click on your new subject in the sidebar.

\- Press \*\*“+ Add Lesson”\*\* and give it a name (e.g., “Derivatives”).



\### 4. Log Your First Mistake

\- Press the `N` key (or click \*\*“+ Add Mistake”\*\* anywhere).

\- Select the subject and lesson.

\- Write a short title (e.g., “Forgot chain rule in composite function”).

\- Fill in the correction and any extra details.

\- Click \*\*“Add Mistake”\*\*.



\### 5. Review

\- From the lesson page, click \*\*“📋 Review Lesson”\*\*.

\- Use the `←` `→` keys to flip through your mistakes.

\- Press `Esc` to exit.



\### 6. Pin the Important Ones

\- Click the `📌` icon on any mistake card to keep it at the top of all lists.



\### 7. Create a Recall Group for Exam Prep

\- Go to \*\*“Recall Groups”\*\* in the sidebar.

\- Click \*\*“+ Create Group”\*\*, give it a name, and select the lessons you want to include.

\- Then click \*\*“📋 Review”\*\* next to the group to study all its mistakes together.



\---



\## 📸 Adding Screenshots

\- In the \*\*Add/Edit Mistake\*\* modal, use the file picker to upload an image \*\*or\*\* simply \*\*paste an image from your clipboard\*\* anywhere inside the modal.

\- The image will be saved along with the mistake.



\---



\## ⚙️ Settings

Access settings via the sidebar:

\- \*\*Dark / Light mode\*\* toggle.

\- \*\*Accent colour\*\* picker.

\- \*\*Export Backup\*\* – downloads a `.json` file with all your data.

\- \*\*Import Backup\*\* – restores data from a previously exported file.

\- \*\*Clear All Data\*\* – permanently deletes everything (requires double confirmation).



\---



\## 💡 Tips for Effective Use

\- Be specific with mistake titles – you’ll recognise them instantly during reviews.

\- Use \*\*tags\*\* (e.g., “sign mistake”, “formula mistake”) to later filter and spot patterns.

\- \*\*Pin\*\* mistakes that keep appearing in exams or that you find particularly tricky.

\- Review a single lesson right after studying it, then use \*\*Recall Groups\*\* to mix topics for a more challenging session.

\- Export your data regularly as a backup.



\---



\## 🛠️ Technical Notes

\- \*\*No dependencies\*\* – everything is hand‑written vanilla HTML/CSS/JS.

\- The entire application is \*\*one file\*\* – portable and easy to share.

\- Data is stored in `localStorage` under the key `mistakes\_recall\_data\_v2`.

\- The app uses CSS custom properties for theming, making it easy to tweak colours.



\---



\## 📜 License

This project is provided for personal educational use. Feel free to modify and share.



\---



\*\*Happy learning! 🎓\*\*  

\*Remember: the best students aren’t the ones who never make mistakes – they’re the ones who never make the same mistake twice.\*

