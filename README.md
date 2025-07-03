# 📦 PresenteCerto — Executive Summary & PRD

## 📌 Overview

**PresenteCerto** is a web platform that acts as a personalized gift recommendation assistant. The user answers a short emotional quiz, and the platform returns 3 to 5 gift suggestions that closely match the recipient’s profile — including emotional descriptions and direct affiliate links for purchase (initially via Amazon Brazil).

The product blends automation, personalization, and SEO strategy to attract organic traffic, help users decide quickly, and convert without any need for logistics or customer service.

---

## 👥 Target Audience

Brazilians between 18 and 45 years old, with disposable income, who:
- Need to buy a gift but don’t know what to choose
- Lack time, ideas, or creativity
- Want a quick, trustworthy, personalized solution

Includes all relationship types: romantic partners, parents, children, friends, coworkers, etc.

---

## 🎯 Value Proposition

> “Discover the perfect gift for anyone in less than 3 minutes.”

- Personalized suggestions based on recipient’s profile
- Emotional explanations: “Why this gift matches this person”
- Real, available products with direct affiliate purchase links
- No login, no sign-up, mobile-first and lightweight experience

---

## ⚙️ Core Features and Flow

### 1. **Landing Page**
- Clear headline + emotional pitch
- Strong CTA: “Start the Quiz”
- Clean, trustworthy design, focused on simplicity and speed

### 2. **Interactive Quiz**
- 6–8 questions such as:
  - Who are you buying for? (mother, friend, girlfriend, etc.)
  - What’s the occasion?
  - Budget range?
  - Interests and personality of the recipient
  - Emotional descriptors (romantic, creative, practical, etc.)
- Use of emojis, friendly buttons, progress bar
- Mobile-first, no login required

### 3. **Recommendation Engine**
- Quiz inputs generate a recipient profile
- Matching logic connects to Amazon product database via API
- Filters by category, interest, price range, and availability
- Personalized description generated via AI (SEO + emotional tone)
- Product updates via Supabase edge functions

### 4. **Results Page**
- Shows 3–5 cards with:
  - Product image, title, price
  - AI-generated emotional description
  - Buy button with affiliate link
- Additional options: view more, retake quiz, save ideas

---

## 📈 SEO & Content Strategy

### Dynamic Profile Pages
Each quiz output generates a unique SEO-friendly URL:

- `/presente-para-mae-criativa`
- `/presente-para-namorado-romantico`

Includes dynamic:
- H1 title
- Meta description
- AI-enhanced human-edited copy

### Initial Blog Articles (3–5 planned)
- “5 gift ideas to impress your mom”
- “How to choose the perfect gift in 3 minutes”
- “Gifts under R$150 for any occasion”

---

## 💰 Monetization

**Primary:** Amazon Brazil affiliate links  
**Future plans:**
- Other affiliate networks (Magalu, Shopee, Americanas)
- Digital products (eBooks, exclusive gift guides)
- Light upsells (extra ideas, saved history, etc.)

---

## 🔄 Retention & Recurrence

- Light email capture at end: “Want gift reminders?”
- Future roadmap:
  - Gift calendar
  - Gifting history
  - Smart suggestions based on past behavior

---

## 🧱 Infrastructure

- **Platform:** Lovable.dev
- **Backend:** Supabase
- **Database tables:** products, categories, profiles, quizzes
- **Edge functions:** daily price/stock sync
- **Content:** AI-generated with human review
- **Design:** emotional, minimalist, modern
- **SEO:** strong from day one via structure and content

---

## 🆚 Benchmark: Giftruly

PresenteCerto improves on key points where Giftruly falls short:
- More emotional, less generic AI copy
- Lighter, more conversational UX
- Stronger SEO for Brazilian search behavior
- Localized design and brand tone
- Built-in strategy for retention and recurring value

---

## 🚀 Strategic Positioning

- **Name:** PresenteCerto  
- **Domain:** [presentecerto.com.br](https://presentecerto.com.br)  
- **Slogan:** “Encontre o presente ideal para qualquer pessoa em poucos minutos.”  
- **Core Focus:**  
  - High conversion during decision moments  
  - Organic traffic via profile-based SEO  
  - Scalable with minimal operational overhead

---

## 📎 Prompt Integration Tip

This file can be referenced in Lovable like this:
https://github.com/pedronader/presentecerto-docs/blob/main/README.md
