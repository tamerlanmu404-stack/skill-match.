# SKILL MATCH — MVP UI Prototype

A responsive bilingual (English/Russian) front-end prototype.

## Run immediately
1. Extract this ZIP.
2. Open `index.html` in a modern browser.
3. Use the left navigation (desktop) or bottom navigation (mobile).
4. Switch language with `EN / RU` and theme with `◐`.

## What's working
- Responsive dashboard layout
- English/Russian interface toggle
- Light/dark theme toggle
- Navigation between dashboard, skills, learning, AI mentor, services, career and portfolio
- Service catalog
- Demo chat interaction

## Important
This is a front-end prototype with sample data. Authentication, persistent user data,
real assessments, file uploads, AI responses, payments, employer workflows and production
security are not connected yet. Do not treat sample skill scores or projects as real credentials.

## Next engineering phase
Move the UI into Expo + React Native + TypeScript for shared web/iOS/Android code,
then connect Supabase Auth, PostgreSQL, Storage and Row Level Security. AI calls must
run through a protected server-side endpoint; never put API secrets in client code.
