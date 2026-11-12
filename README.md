# 👑 Crown Atelier — Premium Dental & Aesthetic Studio

[![Website Status](https://img.shields.io/badge/Status-Active%20%26%20Live-success.svg?style=flat-square)](#)
[![Design](https://img.shields.io/badge/Design-Luxury%20Aesthetic%20Studio-c8a87c.svg?style=flat-square)](#)
[![Built With](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20Bootstrap%205-2c2c2c.svg?style=flat-square)](#)
[![Responsive](https://img.shields.io/badge/Mobile-Fully%20Responsive-blue.svg?style=flat-square)](#)

A luxury, owner-operated dental studio website built for **Crown Atelier**, located in the historic Wicker Park district of Chicago. The website blends clinical excellence, biomimetic dentistry, and bespoke aesthetic care with a warm, editorial design language.

---

## 📌 Table of Contents

- [📖 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [📞 Contact & Alternative Detail Architecture](#-contact--alternative-detail-architecture)
- [🦷 Dental Services & Specializations](#-dental-services--specializations)
- [🎨 Design System & Visual Identity](#-design-system--visual-identity)
- [🛠️ Technology Stack](#️-technology-stack)
- [📂 Project Structure](#-project-structure)
- [🚀 Quick Start & How to Run](#-quick-start--how-to-run)
- [🔍 SEO & Structured Data](#-seo--structured-data)
- [📄 License & Credits](#-license--credits)

---

## 📖 Overview

**Crown Atelier** is an owner-operated, patient-centered dental practice founded by Dr. Ryan Woitas, DMD. The studio specializes in minimally invasive **biomimetic dentistry**, cosmetic smile rejuvenation, restorative crown work, and comprehensive family dental care.

The website provides an engaging, high-converting digital atelier experience featuring:
- Seamless appointment request workflows with validation and toast notifications
- Interactive service details via modal dialogs
- Multi-tier primary and alternative communication channels (Direct phone, 24/7 urgent care line, WhatsApp, multiple emails, and interactive map directions)
- Smooth scrolling, subtle floating particle micro-animations, and responsive cards

---

## ✨ Key Features

### 🏛️ Luxury Atelier Experience
- **Hero Showcase**: Animated background particles, floating depth geometry, gold gradient accents, and clear primary calls to action.
- **Trust Strip**: Quick-glance credentials highlighting owner-operated care, biomimetic methodology, and Chicago location.
- **Why Crown Atelier**: Highlighting core pillars—owner-operated attention, tooth-conserving biomimetic approaches, and state-of-the-art diagnostic imaging.
- **Patient Journey**: Step-by-step breakdown (Consultation &rarr; Treatment Planning &rarr; Personalized Care).

### 🦷 Services & Modals
- **Interactive Service Grid**: General dentistry, cosmetic treatments, dental implants, Invisalign® orthodontics, teeth whitening, and preventive care.
- **Modal Deep-Dives**: Quick-access modal windows explaining consultation procedures and personalized treatment planning.

### 📅 Smart Appointment Booking
- **Validated Form**: Collects full patient name, email, phone number, service preference, preferred location, date, and time.
- **Instant Toast Feedback**: Client-side feedback loop with automatic resets and interactive confirmation alerts.

### 📞 Multi-Channel & Alternative Contact Suite
- **Studio Card**: Prominently displays the flagship studio address in Wicker Park, primary and alternative phone lines, dual emails, and tiered opening schedules.
- **Interactive Action Links**: Click-to-call, WhatsApp direct chat pre-filled message, and Google Maps directions.

### ❓ Expandable FAQ Accordion
- Answers common questions regarding appointment scheduling, first-visit preparation, available services, alternative contact lines, and studio directions.

---

## 📞 Contact & Alternative Detail Architecture

Crown Atelier features primary and alternative communication lines to guarantee accessibility for routine consultations, general inquiries, and emergencies:

| Channel | Detail | Type / Status |
| :--- | :--- | :--- |
| **Primary Phone** | `+1 (312) 847-2769` | General inquiries, appointments, front desk |
| **Alternative Phone** | `+1 (312) 847-2770` | 24/7 Urgent care & after-hours dental emergency |
| **WhatsApp Chat** | Direct WhatsApp link (`+1 312 847 2769`) | Instant messaging & treatment inquiries |
| **Primary Email** | `contact@crownatelier.com` | Concierge, billing, and general correspondence |
| **Alternative Email**| `appointments@crownatelier.com` | Direct scheduling & treatment coordination |
| **Studio Address** | `1959 W Division St, Suite 200, Chicago, IL 60622` | Flagship Wicker Park Studio |
| **Google Maps** | [View on Google Maps](https://maps.google.com/?q=1959+W+Division+St+Suite+200+Chicago+IL+60622) | One-tap navigation link |
| **Weekday Hours** | Monday – Friday: 8:00 AM – 6:30 PM | Standard operating hours |
| **Weekend (Alternative)** | Saturday: 9:00 AM – 3:00 PM | By scheduled appointment |
| **Sunday** | Emergency & Urgent Care On-Call | Emergency coverage |

---

## 🦷 Dental Services & Specializations

1. **Biomimetic Restorations**: Conservative dental techniques preserving natural tooth structure using advanced composite resins and ceramics.
2. **Cosmetic Dentistry**: Custom porcelain veneers, aesthetic bonding, and comprehensive smile makeovers.
3. **Dental Implants**: Permanent, natural-feeling tooth replacements engineered for longevity and bone preservation.
4. **Invisalign® Clear Aligners**: Discretion-focused orthodontic alignment for adults and teens.
5. **In-Office Laser Teeth Whitening**: Fast-acting desensitizing whitening for radiant, healthy smiles.
6. **Preventive Dental Hygiene**: Routine checkups, gentle periodontal therapies, and digital diagnostics.

---

## 🎨 Design System & Visual Identity

The Crown Atelier visual aesthetic is crafted around warm editorial neutrals, brushed warm metallics, and clean typography:

### Color Palette
- **Warm Gold**: `#c8a87c` (Brand primary, icons, badges, borders)
- **Gold Dark**: `#b8925e` (Hover states, button active states)
- **Gold Light**: `#e6d5b8` (Pills, badges, backgrounds)
- **Soft Cream**: `#faf7f2` (Primary website background)
- **Charcoal**: `#2c2c2c` (Body text, deep headers, footer surface)
- **Muted Sage / Soft Teal**: `#6b9080` (Organic health accents)

### Typography
- **Headings & Brand Title**: `Playfair Display` (Classic high-contrast serif)
- **Body & Controls**: `Inter` (Clean, highly legible geometric sans-serif)

---

## 🛠️ Technology Stack

- **Core**: HTML5 Semantic markup
- **Styling**: Vanilla CSS3 + Custom Properties (Variables)
- **Framework & Layout**: [Bootstrap 5.3.2](https://getbootstrap.com/) (Grid system, responsive utilities, modals, accordion, toasts)
- **Iconography**: [Bootstrap Icons v1.11.3](https://icons.getbootstrap.com/)
- **Web Fonts**: [Google Fonts](https://fonts.google.com/) (`Playfair Display`, `Inter`)
- **Scripting**: Vanilla JavaScript (ES6+) for navbar scroll dynamics, client-side appointment validation, and interactive toasts
- **Structured Data**: JSON-LD with [Schema.org/Dentist](https://schema.org/Dentist) metadata

---

## 📂 Project Structure

```bash
Crown-Atelier/
├── .github/
│   └── workflows/          # CI/CD and deployment automation
├── index.html              # Main single-page application with complete sections
└── README.md               # Project documentation & operational guide
```

---

## 🚀 Quick Start & How to Run

### Method 1: Direct Browser Launch
Simply double-click `index.html` or drag it into any modern web browser (Chrome, Edge, Firefox, Safari).

### Method 2: Local Static Web Server
Run using PowerShell / Command Line:

Using **Node.js `npx serve`**:
```bash
npx serve .
```

Using **Python 3**:
```bash
python -m http.server 3000
```
Then navigate to `http://localhost:3000` in your browser.

---

## 🔍 SEO & Structured Data

The website is fully optimized for local Chicago search engine indexing:
- **Title Tag**: `Crown Atelier | Premium Dental & Aesthetic Studio Chicago`
- **OpenGraph & Twitter Card**: Pre-configured social sharing previews.
- **Canonical URL**: Structured for canonical verification.
- **Schema.org JSON-LD**: Explicit `Dentist` type schema embedding postal address, phone numbers, email, geographic coordinates, opening hours, and provider credentials.

---

## 📄 License & Credits

- **Practice**: Crown Atelier Dental Studio
- **Clinical Lead**: Dr. Ryan Woitas, DMD
- **Photography Credits**: Unsplash (Modern clinical interior & studio portraits)
- **License**: Private / Proprietary for Crown Atelier. All rights reserved.
