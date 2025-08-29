# Murmur: Customizable AI-Powered Language Learning Widget

## Overview
## Overview
Murmur (https://murmur-d99.onrender.com/) is a compact desktop widget that quietly integrates into your desktop experience. Learn passively with a list of popular foreign language words and sample sentences—alongside English translations—at scheduled intervals. It stays pinned on top, non-intrusive, and out of your way. Perfect for anyone who wants to soak in new vocabulary passively while working, browsing, or just living life.

Integration of the **OpenAI API** allows you to personalize the tone and context of the sentences you learn. Whether you want to prepare for dating conversations, business meetings, or travel, just select your preference and the widget will serve up relevant content tailored to your goals. It's like language immersion—without having to fly to Paris.

We're just getting started. Upcoming features include text-to-speech, more languages, a refined UI, and even smarter sentence generation. This version is not fully optimized and may have bugs.


> **Note:** This is an early version. The code is not fully optimized or cleaned, and may contain bugs. Future developments will improve efficiency, stability, and add more features.

---

## Features
- **Custom Word Requests**: Uses the OpenAI API to generate words and translations based on your chosen topics, difficulty, or context.
- **Passive Learning**: Displays new words periodically throughout your day without manual intervention.
- **Motivational Quotes**: Integrates AI-generated quotes with language learning to keep you inspired.
- **Multi-Language Support**: Easily extendable to multiple languages by adding language packs.
- **Lightweight Widget**: Minimal system footprint; integrates seamlessly on your desktop or web app.
- **Automated Scheduling**: Fetches words or quotes at scheduled intervals via OpenAI API calls.

---

## How It Works
1. **Input Preferences**: You select the type of words, frequency, and scenario (e.g., “business German words” or “travel phrases”).  
2. **AI Generation via OpenAI API**: Murmur sends requests to the OpenAI API (ChatGPT) to generate a curated list of words, translations, or quotes.  
3. **Scheduled Display**: Words are displayed at your chosen intervals for passive learning.  
4. **Interactive Tracking** (future roadmap): Potential to track learned words and adapt difficulty dynamically.

> **Note:** Please set your own OPENAI API KEY in line 17 of CONFIG.py

---
