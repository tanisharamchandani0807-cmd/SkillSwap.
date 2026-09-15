# SkillSwap

**Your Skills. Your Marketplace.**

## Hackathon ID

`AZIS-XB92FA`

## Project Overview

SkillSwap is a no-login creator gig marketplace where young creators can list their skills and clients can discover and book them.

## Required Features

1. **Post a Gig** — creators add title, category, rate, description, and an animated profile avatar.
2. **Browse & Search** — users can search gigs and filter by category.
3. **Book a Gig** — clients submit their name, project details, and deadline and receive a confirmation.
4. **Creator Dashboard** — creators can view incoming bookings and Accept or Decline them.
5. **My Bookings** — clients can see Pending, Accepted, and Declined bookings.

## Design & Experience

- Animated SkillSwap splash screen and logo
- Modern purple/blue/pink gradient interface
- Multiple creator avatar/profile-picture styles
- Animated visual elements and hover effects
- Responsive layout for desktop and mobile
- 20+ seeded gigs across 12+ categories
- Browser localStorage for demo persistence
- No authentication, login, or signup

## Decision Points

### DP1 — Rejection
When a creator declines a booking, the client can still see the booking as **Declined** and can choose **Find Similar Gigs**.

**Why:** This keeps the booking history transparent and immediately gives the client a next step instead of silently removing the request.

### DP2 — Double Booking
A gig can receive multiple **Pending** booking requests. Only accepted requests are treated as confirmed.

**Why:** Pending requests have not been confirmed by the creator, so allowing them gives creators flexibility to review requests independently.

### DP3 — Discovery
Gigs are ranked **newest first** by default. Search and category filters help users narrow results.

**Why:** New creators get a fair chance to be discovered while users still have simple tools for finding relevant services.

## Standard API

**Not implemented** in this MVP. The project is a self-contained HTML/CSS/JavaScript prototype using browser localStorage.

## Technology

- HTML5
- CSS3
- JavaScript
- Browser localStorage

## How to Run

1. Download the project.
2. Open `SkillSwap.html` in Chrome, Edge, or another modern browser.
3. No installation or server is required.

## Demo Flow

For a 3–4 minute demonstration:

1. Open SkillSwap and show the animated splash/logo.
2. Browse the marketplace and category filters.
3. Open a gig and create a booking.
4. Open Creator Dashboard and Accept/Decline the booking.
5. Open My Bookings and demonstrate the status.
6. If declined, demonstrate **Find Similar Gigs**.
7. Open Post a Gig and demonstrate the animated avatar selection.

## Submission Checklist

- [x] Hackathon ID included in root README
- [x] Post a Gig
- [x] Browse & Search
- [x] Book a Gig
- [x] Creator Dashboard
- [x] My Bookings
- [x] No authentication
- [x] DECISIONS.md included
