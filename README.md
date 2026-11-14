# BolKaam — Bas bolo, kaam ho gaya!

**Just speak. Work gets done.**

I'm Varun, creator of [NextSkill](https://nextskill.pages.dev). I test AI tools hands-on and build in public. BolKaam is my entry for the **Scaler × Wispr Flow hackathon — "India Runs on Voice."**

## The problem

Hundreds of millions of Indians can speak but cannot comfortably type, fill English forms, or use app menus. Every digital system still demands typing first — so the people who need these services most are locked out of them.

## What BolKaam does

You speak **one voice note** in your own language — Telugu, Hindi, English, code-mixed the way India actually talks — and BolKaam returns a **finished piece of work**, not a chat reply.

It is not one chatbot. Each stage uses the best tool for that stage:

- **Hear** — speech recognition built for Indian languages and code-mixed speech
- **See** — a vision model reads the photo you show (street, letter, bill, form)
- **Think** — a frontier reasoning model drafts and asks the one missing question
- **Speak** — the result is read back to you in your language
- **Act** — a workflow layer written in plain code (never a model's guess) produces the final output: the letter, the ledger, the report

Nothing is submitted anywhere automatically. You hear the result and confirm. That final tap is always yours.

## Live demos in this repo

- **`index.html` — Arji (civic complaints):** Speak your problem (a broken water pipe on your street) and get a formal, submit-ready complaint letter with a reference number, a simple summary in your language, and a Day 0 / 3 / 7 follow-up tracker.
- **`khata.html` — Khata (small business):** A shopkeeper speaks one line — *"Ramesh 500 rupees pappu udhaar"* — and the day's ledger and totals update themselves.

Coming next in the same engine: **DoctorBrief** (your symptoms, spoken in your mother tongue, turned into a clean summary to show the doctor — summary only, never a diagnosis) and **Chaduvu** (point your camera at any letter or notice; it is read aloud in simple words, with the action and date pulled out).

## How this was built

BolKaam was built as a live experiment on an AI's own computer, with the screen recording on — the full flow in these demos is exactly what the recording captured, failures included. The demos are single HTML files: no server, no account, no API key. Voice runs in your browser (Chrome).

## Try it

Open the live demo, tap **Sample**, then **Generate** — the finished work appears on screen in seconds.

---

*Team BolKaam · Built for India Runs on Voice (Scaler × Wispr Flow) · ₹0 stack · No facts are ever invented by the system — every letter and ledger is built only from what the user said.*
