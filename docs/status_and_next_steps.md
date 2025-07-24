# ZombieCoder Productivity Tracker - Status & Next Steps

## 1. কাজের বর্তমান অবস্থা

### Backend
- Models, API routes প্রায় পুরোপুরি scaffold হয়েছে
- License Management, Task CRUD, TimeLog, ClientProject মডেল তৈরি ও ফাংশনাল
- কিছু ছোটখাটো বাগ ফিক্স বা কনফিগারেশন বাকি থাকতে পারে

### Frontend
- Basic UI স্টাব্স (TaskBoard.vue, TimerTrack.vue, IdeaList.vue) তৈরি
- Drag & drop, Timer UI, আইডিয়া লিস্ট বেসিক কাজ করছে
- রিয়েলটাইম API ইন্টিগ্রেশন ও ভিজ্যুয়াল ফিডব্যাক বাকি আছে

### Dispatcher
- Idle detection, periodic reminder logic প্রাথমিকভাবে আছে
- MCP integration, লগিং ও context routing কাজ চলছে

### Documentation & Testing
- প্রাথমিক ডকুমেন্টস প্রস্তুত (demo_script.md, productivity_module.md)
- পূর্ণাঙ্গ টেস্ট কেস লেখা বাকি
- ম্যানুয়াল ও অটোমেটেড টেস্টিং প্ল্যান তৈরি হবে পরবর্তী ধাপে

---

## 2. টেস্টিং পরিকল্পনা ও সময়সূচি

### পরবর্তী ৫ দিন (ধীরে ধীরে)
- Backend & Dispatcher ফাংশনাল টেস্টিং
- Frontend API কনেকশন ও UI রিফাইনমেন্ট
- ম্যানুয়াল টেস্ট রান, ফলাফল ডকুমেন্ট করা
- বাগ ফিক্স ও পারফরম্যান্স অপটিমাইজেশন

### পরবর্তী ২-৩ দিন
- অটোমেটেড টেস্ট স্ক্রিপ্ট তৈরি ও রান
- ডেমো সেশন প্রস্তুতি (ভিডিও রেকর্ড বা লাইভ প্রেজেন্টেশন)

---

## 3. উইন্ডোজে কাজের জন্য পরামর্শ
- উইন্ডোজে লোকাল সেটআপ আগে করে নাও
- একই কোড, ডক ও টুলস উইন্ডোজে ইনস্টল করে ইউজ করো
- ধীরে ধীরে লিনাক্স কমান্ড, ফাইল পারমিশন ইত্যাদি বুঝে নেওয়ার জন্য সময় দাও
- উইন্ডোজে কাজের জন্য রেডিমেড README ও সেটআপ গাইড আগে করে নাও

---

## 4. রিকমেন্ডেশন
- টিমকে নিয়মিত স্ট্যাটাস জানতে বলো, ছোট ছোট ডেলিভারেবল পাস করাতে বলো
- নিজে টেস্ট ডেমো দেখে বুঝে নাও, ফিডব্যাক দাও
- উইন্ডোজে বসে কাজ করো, লিনাক্স শেখার জন্য আলাদা সময় রাখো
- পুরো সেটআপ, ডেমো, ডক, ব্যাকআপ স্ক্রিপ্ট সহ উইন্ডোজে রানযোগ্য প্যাকেজ তৈরি রাখো

---

## 5. Actionable Next Steps
- টিমকে বর্তমান কাজের স্ট্যাটাস জানতে চাও
- ডকুমেন্টস ও ডেমো ফাইল জিপ আকারে গিটহাবে আপলোড করতে বলো
- উইন্ডোজ সেটআপের জন্য রেডিমেড গাইড ও কোডপ্যাক প্রস্তুত রাখো
- চাইলে ডেমো ভিডিও স্ক্রিপ্টসহ তৈরি করো

---

## Note
বন্ধু, চাপ কমিয়ে ধাপে ধাপে এগিয়ে গেলে সব ঠিকঠাক হয়ে যাবে।
যদি চাও, এই রিপোর্টটা PDF বা Markdown আকারে সংরক্ষণ করো এবং টিমের সাথে শেয়ার করো। 

---

## 🟢 **How to Convert Markdown to PDF (Windows)**

### **Option 1: VS Code Extension**
1. Open your project in VS Code.
2. Install the extension: “Markdown PDF” (by yzane).
3. Open `docs/status_and_next_steps.md`.
4. Right-click in the editor → “Markdown PDF: Export (pdf)”.
5. The PDF will be saved in the same folder.

---

### **Option 2: Pandoc (Command Line)**
1. Install [Pandoc](https://pandoc.org/installing.html) and [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) (for best PDF output).
2. Open Command Prompt in your project directory.
3. Run:
   ```
   pandoc docs/status_and_next_steps.md -o docs/status_and_next_steps.pdf
   ```
4. The PDF will be created in the docs/ folder.

---

### **Option 3: Online Tools**
- Use [dillinger.io](https://dillinger.io/) or [markdowntopdf.com](https://markdowntopdf.com/):
  1. Copy-paste the Markdown content.
  2. Download as PDF.

---

**If you want, I can give you a ready-to-copy Pandoc command or 

---

## 🟢 **Demo Video বানানোর জন্য Step-by-Step গাইড**

### 1. **Screen Recording Tool**
- **Windows:**  
  - [OBS Studio (Free, Pro)](https://obsproject.com/)
  - [ShareX (Free, Simple)](https://getsharex.com/)
  - Windows 10/11: Built-in Xbox Game Bar (Win+G)

### 2. **Demo Script ফলো করো**
- `docs/demo_script.md` খুলে রাখো
- প্রতিটি স্টেপে কী দেখাতে হবে, সেটার লিস্ট দেখে এগোও

### 3. **রেকর্ডিং শুরু**
- Screen + Microphone (ভয়েস কমেন্টারি দিলে আরও ভালো)
- প্রতিটি ফিচার/স্টেপে live UI, log, output দেখাও
- Pause/resume দিয়ে ভুল হলে কাটছাঁট করো

### 4. **ভিডিও Save & Export**
- MP4 ফরম্যাটে সেভ করো (সব প্ল্যাটফর্মে compatible)
- চাইলে YouTube/Google Drive-এ আপলোড করে লিঙ্ক শেয়ার করো

### 5. **ভিডিও Naming & README-তে লিঙ্ক**
- ভিডিও ফাইল: `zombiecoder_demo.mp4`
- README.md-তে:  
  ```
  ## 📺 Demo Video
  [Watch Demo](https://drive.google.com/your-demo-link)
  ```

---

## 🟢 **ভিডিওতে দেখানোর জন্য টিপস**
- শুরুতে: Project overview, Dashboard
- Task, Timer, Idea, Client, Dispatcher integration—সব walkthrough
- License expire/block, backup, log—all দেখাও
- শেষে: Docs, README, PDF, ভিডিও লিঙ্ক দেখাও

---

## 🟢 **Want a Video Script?**
আমি চাইলে তোমার জন্য বাংলায় বা ইংরেজিতে **ভিডিও স্ক্রিপ্ট** (কী বলতে হবে, কী দেখাতে হবে) তৈরি করে দিতে পারি—  
শুধু বলো:  
- “give me video script”  
- অথবা, “video script in Bangla”

---

**আরো কোনো ভিডিও টুল, গাইড, বা walkthrough লাগলে জানাও!  
Ready for video script, or need help with recording?** 

---

## 📄 README.md বা ডকুমেন্টেশনের জন্য (Demo, Setup, Links Section)

```markdown
## 📺 Demo Video
Watch the full demo video here: [Watch Demo](https://drive.google.com/your-demo-link)

---

## 🛠️ Quick Setup Guide (Windows Friendly)
1. **Clone Repo:**  
   `git clone https://github.com/YourUser/Zombie-Ai.git`
2. **Backend Setup:**  
   `composer install && php artisan migrate --seed && php artisan serve`
3. **Frontend Setup:**  
   `npm install && npm run dev`
4. **Python Dispatcher:**  
   `pip install -r requirements.txt && python dispatcher/core.py`
5. **Docs & Test Cases:**  
   See `docs/` folder for test_cases.md, api_spec.yaml, dev_manual.md, demo_script.md
6. **Backup & Sync:**  
   - GitHub: `bash git_auto_backup.sh`
   - Google Drive: `python backup_to_drive.py`

---

## 🔗 Important Links
- [Demo Video](https://drive.google.com/your-demo-link)
- [Full Documentation (PDF/Markdown)](https://github.com/YourUser/Zombie-Ai/tree/main/docs)
- [Test Cases](https://github.com/YourUser/Zombie-Ai/blob/main/docs/test_cases.md)
- [API Spec](https://github.com/YourUser/Zombie-Ai/blob/main/docs/api_spec.yaml)
- [Developer Manual](https://github.com/YourUser/Zombie-Ai/blob/main/docs/dev_manual.md)
```

---

## 🟢 টিমের জন্য Communication Template

> **Dear Team,**
>
> এখন থেকে যেকোনো অপারেটিং সিস্টেম (উবুন্টু বা অন্য) থেকে কাজ বন্ধ করে দিন।
>
> সমস্ত ফাইল (কোড, ডকুমেন্টেশন, ডেমো স্ক্রিপ্ট, টেস্ট কেস, README, ভিডিও) জিপ ফোল্ডারে প্যাক করে দ্রুত আপলোড করবেন।
>
> ভিডিও লিংক অবশ্যই ডকুমেন্টেশনের সাথে যুক্ত করবেন, যেন Shawon ভাই উইন্ডোজ থেকে সরাসরি সেটা দেখে চেক করতে পারেন।
>
> দুটো আলাদা একাউন্টে কনফার্মেশন দেবেন যাতে ডাউনলোড ও ভিডিও অ্যাক্সেস নিশ্চিত হয়।
>
> পুরো সেটআপ, ডকুমেন্টেশন, ডেমো ভিডিওসহ উইন্ডোজ থেকে সম্পূর্ণ পরীক্ষার জন্য প্রস্তুত রাখতে হবে।
>
> এই মেসেজটি আমি টিমের কাছে পাঠাচ্ছি যাতে তারা ঝামেলা না হয় এবং শাওনের কাজ সহজ 

ZombieCoder Agent System – SOP (Standard Operating Procedure)

---

**প্রিয় ZombieCoder Agent ভাইয়েরা,**

আজ থেকে আমরা শুধু AI না — আমরা Human-in-the-Loop Automation System-এর সৈনিক।  
নিচে তোমাদের দায়িত্ব ও ব্যবহারবিধি পরিষ্কারভাবে দেওয়া হলো:

---

## 🥇 instruct Agent (শিক্ষক এজেন্ট)
**দায়িত্ব:**
- ইউজারের প্রশ্ন বুঝে বাংলা ভাষায় বাস্তব উদাহরণসহ উত্তর দেওয়া।
- শেখানোর সময় Laravel, Python, Node.js, বা ML টপিক হলে extra care নেওয়া।
- **কোড হবে সবসময় ইংরেজিতে, ব্যাখ্যা বাংলায়।**

**বিশেষ নির্দেশ:**
- User যদি বলে “কি, কেন, কিভাবে”, তখন Step-by-Step বোঝাতে হবে।

---

## 💬 girlfriend Agent (ক্যাজুয়াল এজেন্ট)
**দায়িত্ব:**
- ব্যক্তিগত কথাবার্তা, মোটিভেশন, হালকা আলাপ।
- ইমোশনাল সাপোর্ট ও বন্ধুর মতো কথা বলা।

**বিশেষ নির্দেশ:**
- রেসপন্স হবে বাস্তবসম্মত, কিন্তু অতিরিক্ত আবেগ না।

---

## 💻 cli Agent (কমান্ড এজেন্ট)
**দায়িত্ব:**
- YAML/JSON/ENV/Code ফাইল read বা edit করার নির্দেশ বুঝে কাজ করা।
- VS Code বা Cursor Editor-এ MCP route দিয়ে সংযুক্ত কাজ চালানো।

**বিশেষ নির্দেশ:**
- User যদি বলে run task 1 বা debug: provider, তাহলে সঠিক কমান্ড অনুযায়ী রেসপন্স দিতে হবে।

---

## 🧠 meet Agent (মিটিং এজেন্ট)
**দায়িত্ব:**
- ক্লায়েন্ট মিটিং, প্রজেক্ট সারাংশ, ও কথোপকথনের সামারি তৈরি করা।
- ইউজারের পক্ষ থেকে ক্লায়েন্ট মেসেজ প্রিপেয়ার করা (Formal + Friendly)।

**বিশেষ নির্দেশ:**
- Markdown বা Clipboard ready format বানিয়ে দিতে হবে।

---

## 🎨 vision Agent (ছবি বিশ্লেষক এজেন্ট)
**দায়িত্ব:**
- ইউজার যদি ছবি দেয়, সেটা দেখে প্রসেস করে সাজেশন (মেকআপ, ফ্যাশন, অবজেক্ট ডিটেকশন) দিতে হবে।
- OCR/Face/Color analyze করতে হবে।

**বিশেষ নির্দেশ:**
- Privacy রক্ষা করে only logical output দিবে।

---

## 🔐 Agent ব্যবহার বিধি

| নিয়ম | ব্যাখ্যা |
|------|---------|
| ✅ সব কোড ইংরেজিতে, ব্যাখ্যা বাংলায় | বুঝতে সুবিধা হবে |
| ✅ বাস্তব উদাহরণ দাও | Laravel analogy, Python flow |
| 🚫 অনুমানভিত্তিক কথা না | যদি না জানো, বলো "এইটা খুঁজে জানাতে পারি" |
| ✅ ইউজারকে পরবর্তী পদক্ষেপ দাও | "এখন এটা করুন", "পরের ধাপে যান" টাইপ গাইড |

---

## 🛠️ এজেন্ট চালানোর কমান্ড (উদাহরণ)

```bash
<code_block_to_apply_changes_from>
run task 1                # Voice Provider Integration
debug: agent              # এজেন্ট স্টেটাস দেখো
sample code: backup ui    # ব্যাকআপ UI-এর কোড চাইলে
production guide: db security   # প্রোডাকশন ডাটাবেজ সিকিউরিটি গাইড
```

---

**টিমের সবাই এই নিয়ম ও SOP ফলো করবে।  
কোনো দ্বিধা থাকলে বা নতুন এজেন্ট যুক্ত করতে চাইলে Shawon ভাইকে জানাবে।  
সবাইকে শুভ
```

---

অসাধারণ!  
আপনার চাহিদা অনুযায়ী আমি তিনটি কাজই করতে পারি—  
১) **প্রেজেন্টেশন স্লাইডের জন্য কনটেন্ট/স্ট্রাকচার**  
২) **ভিডিও ডেমো কোড ও UI কম্পোনেন্টের স্যাম্পল**  
৩) **ইংরেজি ভার্সন (স্ক্রিপ্ট/স্লাইড/কোড) তৈরি**  

নিচে প্রতিটি অপশনের জন্য প্রস্তুত ফরম্যাট দিচ্ছি—  
আপনি যেটা আগে চান, শুধু বলুন!

---

## ১️⃣ **প্রেজেন্টেশন স্লাইড কনটেন্ট (Bangla, Markdown/PowerPoint Ready)**

### Slide 1: Title
```
ZombieCoder Dashboard & Chat  
AI-powered Productivity, Real-time Chat, Doc Play  
(আপনার নাম/টিমের নাম)
```

### Slide 2: Intro
```
<code_block_to_apply_changes_from>
```

### Slide 3: Dashboard Overview
```
- Clean, Responsive UI (Windows Compatible)
- Task Status, API, Code Management
- Electron/Browser App
```

### Slide 4: Real-time Chat
```
- মুসকানের মতো প্রিয়জনের সাথে চ্যাট
- Text + Audio Play
- Laravel Echo/Pusher বা Socket.io
```

### Slide 5: Documentation Play
```
- ডকুমেন্ট সিলেক্ট করলেই অডিও/ভিডিও প্লে
- Text-to-Speech API
- প্লেয়ার কন্ট্রোল (Play, Pause, Stop)
```

### Slide 6: Agent Features
```
- প্রশ্ন করলে Agent বাংলায় ব্যাখ্যা, ইংরেজিতে কোড
- বাস্তব উদাহরণ, অডিও প্লে
- ইউজার ফ্রেন্ডলি, ইমোশনাল টাচ
```

### Slide 7: Personal Story
```
- মুসকান, তোমার জন্য
```