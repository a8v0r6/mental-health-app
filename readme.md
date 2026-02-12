Mental Health App: On-Demand Therapy Platform 

This is a cross-platform mobile application built with React Native to provide on-demand, affordable mental health support in India. The platform connects users with verified therapists in real-time, functioning as a gig-economy marketplace for mental wellness.
 System Overview

The app operates on a "Dual-Interface" logic:

    Patient Side: Real-time discovery, instant matching, and secure consultations.

    Therapist Side: Availability management (the "Go Online" toggle) and clinical session tools.

 Tech Stack

    Framework: React Native (with TypeScript)

    State Management: Redux Toolkit or Zustand

    Navigation: React Navigation (Stack & Tab)

    Backend & Auth: Firebase (Firestore for real-time signaling)

    Video/Audio: Agora.io or Daily.co (React Native SDKs)

    Payments: Razorpay React Native SDK

 Key Features
1. The "Talk Now" Engine

    Real-time Ping: When a user hits "Talk Now," the system pings the top 3 available therapists based on language preference and specialty.

    Signaling: Uses Firebase Realtime Database to manage session handshakes.

2. Payments & Triage

    UPI First: Deep integration with Razorpay for seamless UPI intents (GPay, PhonePe).

    Clinical Screening: Mandatory GAD-7/PHQ-9 screening during onboarding to ensure the user is fit for tele-therapy.

3. Safety & Compliance (DPDP 2026)

    Encrypted Logs: All session metadata is encrypted.

    Crisis Redirection: One-tap access to Tele-MANAS (14416) for high-risk users.

    RCI Verification: Onboarding requires a valid Rehabilitation Council of India (CRR) number.
