# 👋 Hey there! Welcome to AI-Vision Studytracker

I wanted an AI study timer that only ticks when I'm actually sitting at my desk. 

Originally, I thought about using a cloud AI or Python, but I quickly ran into three huge roadblocks:
1. **Privacy:** I really didn't want my webcam sending pictures of my room to a cloud server every minute.
2. **Battery Life:** I use a 2019 Intel Mac, and running continuous AI vision in the background turns my laptop into a jet engine and kills the battery.
3. **Bloat:** When I tried installing developer tools on my Mac, it asked for **16.6 GB** of disk space just to get started!

So, I built **FocusCam AI**—a single, 8 KB HTML file that runs right inside your web browser. No Python, no heavy downloads, and zero data ever leaves your computer.

---

## 💡 What It Actually Does

* **Watches the clock so you don't have to:** If you sit down to study, the timer runs. If you walk away to grab water, it pauses automatically and welcomes you back when you sit down.
* **Doesn't fry your battery:** Instead of scanning your face 30 times a second, it gently wakes up the AI detector once every 4 seconds. Your laptop stays cool and quiet.
* **Talks to you like a study buddy:** It greets you by name, tells you when you've hit a 50-minute study streak so you can stretch, and calls you back to your desk when your 5-minute break is over.
* **Realistic posture checks (Optional):** Most students lean forward when writing in a notebook—we don't all sit like statues! Posture alerts are turned **off** by default, or you can sit in your normal comfortable position and click **"Set My Posture"** so it adapts to *you*.
* **Logs your hard work:** Every time you stop a session, it saves your date, subject, and focused time right in your browser, and lets you export everything to a CSV/Excel sheet.

---

## 🚀 How to Use It (Takes 10 Seconds)

You don't need to install anything—whether you're on **Mac, Windows, or Linux**:

1. Download the `index.html` file from this repository.
2. Double-click it to open it in your browser (**Google Chrome** or **Microsoft Edge** have the best-sounding voices!).
3. Click `"Scholar"` at the top-left to type your own name.
4. Pick a voice you like, type what subject you're studying, and hit **Start Studying**.

---

## 🔒 A Quick Note on Privacy

Your webcam feed stays **100% inside your browser tab's temporary memory**. Nothing is recorded, nothing is saved to your hard drive, and nothing is ever sent over the internet. Even your study logs and username are stored locally on your own device (`localStorage`).

---

## 🛠️ Want to Tweak It?

The entire app lives inside `index.html`. You can open it in Notepad or TextEdit and change whatever you want—adjust the 50-minute break timer, change the colors, or rewrite what the voice assistant says to you.

If this helps you stay focused during exams, feel free to ⭐ star the repo or share it with a friend!
